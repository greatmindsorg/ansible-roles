# ansible-roles
A set of Ansible roles for provisioning development boxes.

## Django
For the time being after following the necessary steps in the development-standards, run:
- ssh into the vagrant box
- cd into the project folder and run `source bin/activate`
- create the project by running `django-admin startproject [your-project-name]`
- as root restart supervisor `supervisorctl restart all`
