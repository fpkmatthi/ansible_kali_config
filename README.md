Role Name
=========

Ansible role to configure a fresh Kali VM.

Role Variables
--------------

Most important are:

- burpsuite_pro_license_key
- nessus_user
- nessus_user_pw
- nessus_license
- dotfile_git_url

Check defaults/main.yml for a full list of vars

Dependencies
------------

- Virtualbox
- Kali VM with Ansible

```
sudo apt install ansible
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - ansible_kali_config

License
-------

BSD

