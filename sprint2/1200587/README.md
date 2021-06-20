RCOMP 2020-2021 Project - Sprint 2 - Member 1200587 folder
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
|310|B5F0|10.125.184.0/26|255.255.255.192|10.125.184.0 - 10.125.184.63|10.125.184.1 - 10.125.184.62|10.125.184.63|
|311|B5F1|10.125.182.64/26|255.255.255.192|10.125.182.64 - 10.125.182.127|10.125.182.65 - 10.125.182.126|10.125.182.127|
|312|B5DMZ|10.125.178.0/24|255.255.255.0|10.125.178.0 - 10.125.178.255|10.125.178.1 - 10.125.178.254|10.125.178.255|
|313|B5VoIP|10.125.184.64/26|255.255.255.192|10.125.184.64 - 10.125.184.127|10.125.184.65 - 10.125.184.126|10.125.184.127|
|314|B5WIFI|10.125.181.192/26|255.255.255.192|10.125.181.192 - 10.125.181.255|10.125.181.193 - 10.125.181.254|10.125.181.255|


