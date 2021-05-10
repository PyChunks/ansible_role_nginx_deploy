Role Name
=========

Installs and configures a basic Nginx website.

Requirements
------------

This role is dependant on the `Ansible Posix collection` available from Ansible-galaxy.

```
ansible-galaxy collection install ansible.posix
```

Role Variables
--------------

Variables that need to be set:
```yaml
domain:
```

The Fully Qualified Domain Name (FQDN) of your site.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars: 
        domain: www.example.com
      roles:
         - ansible_role_nginx_deploy 

License
-------

BSD

Author Information
------------------

Created by Vincent D-Gauthier
