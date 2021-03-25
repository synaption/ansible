# ansible
command and output 
''' bash
(base) ubuntu2004@ubuntu:~/ansible$ ansible-playbook rebootOLD.yml -i /etc/ansible/hosts/hosts.ini -b -c ssh

PLAY [gsdDev] *********************************************************************************************************************************************************************************************

TASK [Gathering Facts] ************************************************************************************************************************************************************************************
[DEPRECATION WARNING]: Distribution debian 10.8 on host raspbberrypi-gsd-dev should use /usr/bin/python3, but is using /usr/bin/python for backward compatibility with prior Ansible releases. A future 
Ansible release will default to using the discovered platform python for this host. See https://docs.ansible.com/ansible/2.10/reference_appendices/interpreter_discovery.html for more information. This 
feature will be removed in version 2.12. Deprecation warnings can be disabled by setting deprecation_warnings=False in ansible.cfg.
ok: [raspbberrypi-gsd-dev]
ERROR! the field 'hosts' is required but was not set
'''
