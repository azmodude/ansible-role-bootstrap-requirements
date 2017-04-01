Bootstrap-Requirements
=========

Install requirements depending on distribution for Ansible to function correctly. 
Think of it as bootstrapping a box/container to include the absolutely required packages.

Example Playbook
----------------

Make sure `gather_facts` is set to `False` for the play because Python might not be available (yet).

    - hosts: all
      become: yes
      gather_facts: False
      roles:
        - azmodude.bootstrap-requirements

License
-------

BSD 3-clause.

Author Information
------------------

Gordon Schulz.
