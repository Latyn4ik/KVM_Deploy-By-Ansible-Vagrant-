### Deploy 3 KVM by Vagrant and Configure by Ansible 
1. VM_1 - Apache Server + Wordpress (for Quick Simple Site).

    OS: Ubuntu18.04

2. VM_2 - MySQL Database Server.

    OS: Ubuntu18.04

    Databases: Wordpress and Wordpress.

3. VM_3 - Zabbix Server (Monitoring)

    OS: CentOS 7

Ansible requirements:
* ufw use in asnible - ``` ansible-galaxy collection install community.general ```

Zabbix version 4.0
