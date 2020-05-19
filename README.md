# ansible
Installation of ansible and some playbooks to run in Server.

#Create host.ini in you folder
[all:vars]
ansible_user=centos
ansible_ssh_private_key_file=test-ravindra.pem 

[all]
server IP

```sh
ansible-playook playbookname.yml -i host.ini
```
