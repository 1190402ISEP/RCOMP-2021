RCOMP 2020-2021 Project - Sprint 2 - Member 1190742 folder
===========================================

## Building 3 ##

###Information

- End user outlets on the ground floor: 40 nodes
- End user outlets on floor one: 44 nodes
- Wi-Fi network: 60 nodes-Local servers
- Local servers, administration workstations, and industrial machines (DMZ): 250 nodes
- VoIP (IP-phones): 40 nodes


###Distribution

|VlANID |VLANName|Subnet Address|Net Mask|Range of addresses|Usable IPs|Broadcast Address|
|----|----|----|----|----|----|----|
|300|B3F0|10.125.183.128/26|255.255.255.192|10.125.183.128-10.125.183.191|10.125.183.129-10.125.183.190|10.125.183.191|
|301|B3F1|10.125.182.128/26|255.255.255.192|10.125.182.128-10.125.182.191|10.125.182.129-10.125.182.190|10.125.182.191|
|302|B3DMZ|10.125.176.0/24|255.255.255.0|10.125.176.0-10.125.176.255|10.125.176.1-10.125.176.254|10.125.176.255|
|303|B3VoIP|10.125.183.192/26|255.255.255.192|10.125.183.192-10.125.183.255|10.125.183.193-10.125.183.254|10.125.183.255|
|304|B3WiFi|10.125.181.64/26|255.255.255.192|10.125.181.64-10.125.181.127|10.125.181.65-10.125.181.126|10.125.181.127|
