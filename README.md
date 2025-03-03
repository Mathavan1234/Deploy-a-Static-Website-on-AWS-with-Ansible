# Deploy a Static Website on AWS with Ansible

ansible.cfg - This is the configuration file to test the connection between Ansible Web Server and EC2 Web Servers.
inventory - This file consists the Private IP Addresses of both the Web Server AZ1 and AZ2 across 2 availability zones (Created for High Availability).
deploy-jupiter-website.yaml/yml - This is the ansible script in yml format which converts the linux commands into the ansible understandable format (Mainly used to install the static web contents into the Ansible Web Server). 

For step by step guideline:
Medium Article :- https://medium.com/@smaddy799/b8a96d0ca852


