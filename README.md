# vyos-zabbix

# Template for zabbix 4
VyOS-zabbix-agent.xml without snmp

# Template VyOS for SNMPv2
Feautures
Low level discovery (lld) for interfaces and their aliases.
Memory/CPU Utilization
VRRP state changes
BGP neighbors autodiscovery

Triggers:
high CPU utilization
low RAM memory
VRRP state was changed
BGP neighbor state not established.

On zabbix Configuration => Templates => Import => Template_OS_VyOS_SNMPv2.xml
