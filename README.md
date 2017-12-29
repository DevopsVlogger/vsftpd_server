# vstpd_server
**This Ansible role is to Install and Configure vsftpd server on RHEL/CentOS 7.x**

Download or Clone the following repository to your local machine.
Run the following command from your Ansible controller node -
#ansible-playbook vsftpd_server/test_vsftp.yml -i vsftpd_server/inventory -b -u root

**Role Variables**
defaults/main.yml

**Name	              Default Value	        Description**


vsftpd_shares_root	  /srv/shares	          The default ftp directory where your shares will be placed


vsftpd_shares	          -	                  List of dicts defining the ftp shares that need to be created


vsftpd_groups	          -                   List of dicts defining the groups that need to be created


vsftpd_users	          -	                  List of dicts defining the users that need to be created


**Dependencies**
This role has no depencies

Some Git specific information if you want to make changes to any of the yml files as per your requirement.
Once you make changes to any of the repo file run the following commands in order to push the changes to master repo ->

#git status

#git add "File Name"

#git status

#git commit -m "Changed blah blah in file"

#git push -f origin master


