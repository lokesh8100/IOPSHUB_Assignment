# IOPSHUB_Assignment
#########
create 2 aws ec2 linux machine and access them via putty. connect node to master. create ansible playbook on master as user.yml write playbook. to check the playbook syntax is ok or not : ansible-playbook user.yml --syntax-check

to execute the playbook: ansible-playbook user.yml

user will create into remote node go to node to check user is created or not : cat /etc/passwd

here you will see the created user at bottom and path which assign in ansible playbook user.yml.

######
INSTALL httpd package on remote node

create role as main.yml
create playcook as master.yml

to check the synatx of  the playbook
ansible-playbook master.yml --syntax-check


to execute the playbook to install httpd package on remote node
 ansible-playbook master.yml 

to check httpd is installed on node:
 
which httpd
