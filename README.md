Oracle DB Ansible Playbook
==========================

## Detailed info

Ansible playbook to configure a CentOS/RHEL/Oracle Linux 7 server with Oracle 12c R1 Enterprise Edition Database

Download from Oracle support the Oracle installation files: 
- linuxamd64_12102_database_1of2.zip
- linuxamd64_12102_database_1of2.zip
and put them to folder roles/oracle-install/files inside checkout folder

After a few minutes a virtual machine with Oracle Database will be ready for you without any further configuration. You can access the Enterprise Manager Express using sys/sysdba and “oracle” as password.

https://oradb3.private:5500/em

## Licence

Forked project. Copyright (c) 2018 Stavros Kalapothas (aka Stevaras) <stavros@ubinet.gr>.
It is free software, and may be redistributed under the terms of the GNU Licence.