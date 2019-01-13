vagrant-Zabbix
==============

This VagrantFile provides a Zabbix 3.2 server installed on Ubuntu Trusty.   

After vagrant up, connect to the VM on localhost:8080/zabbix/setup.php and complete the Installation. 

Note: you will want to set the mysql User to root and Password to zabbix to complete the install.

MySQL root password: zabbix



add snmp package to Zabbix server
---------------------------------

apt-get install snmp



```

Cisco Router commands
---------------------

snmp-server community public <string> RO 
snmp-server host <IP of ZabbixServer> version 2c public udp-port 161



snmp walk 
---------

snmpwalk -v2c -c <string> <IP of ZabbixServer>

