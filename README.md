# ansible-cisco-templater
Basic Cisco Template Config Example in Ansible

Clean up all the default off Cisco routers, and apply a clean standard config easily. I use this when preparing larger network rollouts.

Edit inventory file for your environment variables.
This is a basic example of IOS switches and routers.

Example Usage
ansible-playbook template-routers.yml
or
ansible-playbook template-switches.yml

Generates template files in "config" folder.

License: GPL
