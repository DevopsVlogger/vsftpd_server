# vstpd_server
Install and Configure vsftpd server ->

ansible-playbook vsftpd_server/test_vsftp.yml -i vsftpd_server/inventory -b -u root

Once you make changes to any of the repo file run the following commands in order to push the changes to master repo ->

#git status

#git add handlers/main.yml

#git status

#git commit -m 'added handler entry for firewalld service"

#git push -f origin master
