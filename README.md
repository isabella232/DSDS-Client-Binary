# DSDS(Data Set Distribution Service)

DSDS is Client/Server Mode, this introduction will show how to deploy DSDS with Ansible.

Default Configuare File: /etc/ansible/ansible.cfg

# Services Requirement: 
1. Apache 
2. PostgreSQL
3. GridFTP

# Install PostgreSQL:
1. Install the database software
2. Ensure the database service is running 
3. Created the database inside the database management system
4. Create a database user who has the appropriate permissions for the database system 
5. Configure DSDS application with the database user credentials and connection information

# Commands:
ansible-playbook -i /home/centos/DSDS-wtsgi-master/inventory main.yml --vault-password-file /home/centos/DSDS-wtsgi-master/vault_pass.txt

# DSDS-Client-Ansible
