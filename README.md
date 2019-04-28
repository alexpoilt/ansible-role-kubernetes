Up cluster Kubernetes
====================

This role install and configure cluster k8s

Example Playbook
----------------

It's role have file exemple playbook for instal cluster k8s, you must to use this exemple. 

You must add the group master and workers on your file /etc/hosts:
```
...
[master]
master1 ansible_host=<you.ip> ansible_user=root

[workers]
node01 ansible_host=<your.ip> ansible_user=root
node02 ansible_host=<your.ip> ansible_user=root
...
```

License
-------

BSD

Author Information
------------------

Alvaro Bacelar - IT Specialist
