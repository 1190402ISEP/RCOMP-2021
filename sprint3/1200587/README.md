RCOMP 2020-2021 Project - Sprint 3 - Member 1200587 folder
===========================================

## Building 5 ##

### Information ###
- End useroutlets on the ground floor: 40nodes
- End user outlets on floor one: 45nodes
- Wi-Fi network: 60 nodes
- Local servers, administration workstations, and industrialmachines(DMZ): 250nodes
- VoIP (IP-phones): 40 nodes


### Distribution ###

|VLANID |VLANName|Subnet Address|Net Mask|Range of addresses|Useable IP's|Broadcast Address|
|----|----|----|----|----|----|
|310|B5F0| 10.125.185.128/26 | 255.255.255.192 | 10.125.185.128 - 10.125.185.191 | 10.125.185.129 - 10.125.185.190 | 10.125.185.191 |
|311|B5F1| 10.125.185.64/26 | 255.255.255.192 | 10.125.185.64 - 10.125.185.127 | 10.125.185.65 - 10.125.185.126 | 10.125.185.127 |
|312|B5DMZ| 10.125.184.0/24 | 255.255.255.0 | 10.125.184.0 - 10.125.184.255 | 10.125.184.1 - 10.125.184.254 | 10.125.184.255 |
|313|B5VoIP| 10.125.185.192/26 | 255.255.255.192 | 10.125.185.192 - 10.125.185.255 | 10.125.185.193 - 10.125.185.254 | 10.125.185.255 |
|314|B5WIFI| 10.125.185.0/26 | 255.255.255.192 | 10.125.185.0 - 10.125.185.63 | 10.125.185.1 - 10.125.185.62 | 10.125.185.63 |


