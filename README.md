# ansible-role-sysgroups
Ansible role for management of groups on an Ubuntu host

###### Variable Definition:

   group_vars/dev-all.yml

    sysgroups:
    - name: somenewgroup
    - name: anothernewgroup
      gid: 1234
      system: yes
    - name: yetanothergroup
      state: absent
