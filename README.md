# ansible-cisco-templater
##Basic Cisco Template Config Example in Ansible

This is a basic example of IOS switches and routers.

Clean up all the default off Cisco routers, and apply a clean standard config easily. I use this when preparing larger network rollouts.

##Install Ansible
The best way on Windows is Babun
http://babun.github.io

Download the installer from the Babun site, then this is a quick start to get ansible up and running.
Then in the babun shell run this to jumpstart the ansible bootstrap.

Run this inside the new Babun Shell
curl -s https://raw.githubusercontent.com/tiangolo/ansible-babun-bootstrap/master/install.sh | source /dev/stdin

###Then install some other dependancies.
####Run these in Babun: (you can copy paste the whole block)
* pact install python-yaml
* pact install python-setuptools python-ming
* pact install libxml2-devel libxslt-devel libyaml-devel
* pact install python-jinja2


Other platforms, apt-get install ansible, npm install ansible, etc...

##Example Usage
Edit inventory file for your environment variables.

###ansible-playbook template-routers.yml

or

###ansible-playbook template-switches.yml
  

Generates template files in "config" folder.

####License: GPL
