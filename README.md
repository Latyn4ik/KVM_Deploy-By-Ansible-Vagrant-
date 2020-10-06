### Deploy 3 KVM by Vagrant and Configure by Ansible 
1. VM_1 - Apache Server + Wordpress (for Quick Simple Site).

    OS: Ubuntu18.04

2. VM_2 - MySQL Database Server.

    OS: Ubuntu18.04

    Databases: Wordpress and Wordpress.

3. VM_3 - Zabbix Server (Monitoring)

    OS: CentOS 7

Zabbix version 4.0

KVM-QUEMY requirements:
* ``` sudo apt install qemu qemu-kvm libvirt-daemon libvirt-clients bridge-utils virt-manager ```
* ``` sudo gpasswd -a $USER libvirt ```  ( Add your user to libvirt group)
* ``` sudo systemctl status libvirtd ``` (  Check that libvirt server is running)

Ansible requirements:
* ufw use in asnible - ``` ansible-galaxy collection install community.general ```

Vagrant requirements:
* ``` sudo apt-get install libxslt-dev libxml2-dev libvirt-dev zlib1g-dev ruby-dev ```
* ``` vagrant plugin install vagrant-libvirt ```
