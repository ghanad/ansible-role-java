[![Actions Status](https://github.com/ghand/ansible-role-java/workflows/CI/badge.svg)](https://github.com/ghanad/ansible-role-java/actions)


Ansible Role: Java
=========

An ansible role that install Java on remote machine with java tar file. to use this role you need jdk tar.gz file.

Requirements
------------

put jdk tar.gz file in `/opt/` local machine.


Variables
-----------
```JAVA_SRC_DIR```

copy java from this directory in local machine. defult path is `/opt/`

```JAVA_DIR_HOME```

copy java files to this directory in remote machine. defult path is `/opt/`

Example playbook
-------------
```
- hosts: all
  roles:
    - java
```
