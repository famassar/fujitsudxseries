# fujitsudxseries
Template Zabbix for Storages Fujitsu Eternus DX series

Tested with Zabbix 5.0 and MIB R153 on DX100 and DX200

Features:

- Fixed items for generic values
- Autodsicovery functions for CM Memory, CPU, Disks, PSU, Raid, Temperature, Volumes

1) Determine which MIB you have (this is also in the name of mib file, i.e "FJDARY-E153.MIB" says the versioni is 153)

2) Set correct initial OID matching your version in the {$BASE_OID} macro (i.e for 153 version this is 1.3.6.1.4.1.211.1.21.1.153)

3) Import the value mapping table
 
4) Apply to your storage Host

5) Enjoy!
