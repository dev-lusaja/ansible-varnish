Ansible commands
---------------

**Install ansible on OS**

~~~~~
$ brew install ansible
$ brew install ssh-copy-id
~~~~~~

**Generate private key**
~~~~
$ ssh-keygen
~~~~

**Install private key**
~~~~~~
$ ssh-copy-id -i ~/.ssh/id_rsa.pub <user>@<server_ip>
~~~~~~~

**Execute a playbook**
~~~~~~
$ ansible-playbook playbook.yml
~~~~~~~

**configure your ansible host (only OS): **
~~~~~~
/etc/ansible/hosts
~~~~~~

**Verify server conectivity**
~~~~~~
$ ansible [host] -m ping -u devops
~~~~~~

**NOTE:**
- We need a sudoer user