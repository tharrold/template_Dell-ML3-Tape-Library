# template_Dell-ML3-Tape-Library
Zabbix Template for Dell ML3 Tape Library

This is a simple Zabbix template to apply to Dell ML3 tape libraries.
There are no macros, and only a few value mappings.  This template will discover tape drives, and create several items for each discovered drive.

Zabbix Version: 7.4

Instructions:

-Create your host (ML3 library)
-Setup SNMPv2 or SNMPv3 on the ML3 library
-Configure Zabbix host with proper SNMP community name, or SNMPv3 credentials
-Add this template to the host
