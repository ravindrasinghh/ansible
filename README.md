# ansible
Installation of ansible and some playbooks to run in Server.
```sh
#Create host.ini file in you folder path 
[all:vars]
ansible_user = centos
ansible_ssh_private_key_file=test-ravindra.pem 

[all]
server IP
```

```sh
#Run command
ansible-playook playbookname.yml -i host.ini
```
