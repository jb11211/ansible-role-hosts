hosts
=====

This Ansible role adds host records to `/etc/hosts`.


Role Variables
--------------

    save_hosts: [] # hosts to save


Example configuration
---------------------

save_hosts:
    - name: example.net
      ip:   8.8.8.8
    - name: example.com
      ip:   8.8.4.4


License
-------

Public Domain


Author Information
------------------

Serhiy Oplakanets <serhiy@oplakanets.com>
