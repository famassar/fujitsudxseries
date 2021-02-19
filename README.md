# fujitsudxseries
Template Zabbix for Fujitsu Storages DX series

Tested with Zabbix 5.0 and MIB R153

Features:

- Fixed items for generic values
- Autodicovery functions for CM Memory, CPU, Disks, PSU, Raid, Temperature, Volumes

1) Determine which MIB you have (this is also in the name of mib file, 
i.e "FJDARY-E153.MIB" says the versioni is 153)

2) Set correct initial OID matching your version in the {$BASE_OID} macro (i.e for 153 version this is 1.3.6.1.4.1.211.1.21.1.153)

3) Apply to your storage Host

4) Enjoy!
