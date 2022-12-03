#Task 2 -- Ansible

>Task name:

Manage WebServers through Ansible.

>Task description:

Write the Ansible script to install and test the web server with ping command in a single playbook. Choose either Apache or Nginx server based on your own preference.

● Name the playbook WEB SERVER INSTALLATION AND TESTING.

● TWO tasks must be successful to get a grade (Installation and Testing).

● Take screenshots indicating the success of your actions and save script files and related docs. 

>Task preparation

Enable the SSH server.

![SSH server](https://user-images.githubusercontent.com/58246129/192381660-7b00e904-41e4-4a57-a39f-88c577eaf911.png)


Open the ansible directory in VS Code.

![ansi](https://user-images.githubusercontent.com/58246129/192381752-55b1a4de-9397-4be0-b7a1-3ec372f16722.png)

Edit the Ansible inventory file 

Open the ansible-apache and add a line in the ‘host’ file.

![ansi-ap](https://user-images.githubusercontent.com/58246129/192382008-6b2aa8b5-d667-4404-8aee-46d650c90e55.png)

![ansiap](https://user-images.githubusercontent.com/58246129/192382030-102a4249-f14e-4efe-97bd-6faec8f5ff35.png)


Edit the ansible.cfg file

The ansible.cfg file tells Ansible where to find the inventory file and sets certain default parameters.

Ping the web server to check for connection. 

![ping](https://user-images.githubusercontent.com/58246129/192382117-b326c706-1de7-435f-8011-a05e8bae3f2b.png)

Check if Ansible can communicate with the webserver

![commu](https://user-images.githubusercontent.com/58246129/192382185-9f73c1c1-338a-4844-8698-8b7f50c778b7.png)


>Task implementation 

Creating Ansible Playbook to Automate Web Server Installation

Create a file named ‘test_apache_playbook.yaml’

![fil](https://user-images.githubusercontent.com/58246129/192382427-25b4a2ae-e622-41c8-bbef-fa61d0ce6f7d.png)

Run the Ansible playbook

![P_book](https://user-images.githubusercontent.com/58246129/192382441-bff569ea-c17e-4543-b4b1-818d83ad1c4c.png)

For Ansible to install apache, create a new file in the ansible-apache directory and write:

![ins](https://user-images.githubusercontent.com/58246129/192382456-115cab68-608b-484d-9442-10c474759d65.png)

Run the Ansible to install Apache

![inst](https://user-images.githubusercontent.com/58246129/192382658-47a9d406-71b5-4cf7-9255-9c753ca7415a.png)

Verify if Apache has been installed.

![veri](https://user-images.githubusercontent.com/58246129/192382685-e79f0baa-5e1f-4010-8745-55faad0314b1.png)

Run the ip address on the browser to get to the Apache home page.

![apache](https://user-images.githubusercontent.com/58246129/192382868-5adb7f6d-ebd9-45b3-8152-07536166d8c8.png)



