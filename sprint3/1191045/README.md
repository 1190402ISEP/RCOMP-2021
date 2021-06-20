RCOMP 2020-2021 Project - Sprint 3 - Member 1191045 folder
===========================================

# Building 4 ##

##Correções do Sprint2

| Vlan ID   | VTP Domain        | Subnet address        | Netmask               | Range of addresses                    | Useable IPs                           |
| --------- | ----------------- | --------------------- | --------------------- | ------------------------------------- | ------------------------------------- |
| --        | **Building 4**    | **10.125.182.0/23**   | **255.255.254.0**     | **10.125.182.0 - 10.125.183.255**     | **10.125.182.1 - 10.125.183.254**     |
| 305       | Ground Floor      | 10.125.183.128/26     | 255.255.255.192       | 10.125.183.128 - 10.125.183.191       | 10.125.183.129 - 10.125.183.190       |
| 306       | Floor One         | 10.125.183.64/26      | 255.255.255.192       | 10.125.183.64 - 10.125.183.127        | 10.125.183.65 - 10.125.183.126        |
| 307       | DMZ               | 10.125.182.0/24       | 255.255.255.0         | 10.125.182.0 - 10.125.182.255         | 10.125.182.1 - 10.125.182.254         |
| 308       | VoIP              | 10.125.183.192/27     | 255.255.255.224       | 10.125.183.192 - 10.125.183.223       | 10.125.183.193 - 10.125.183.222       |
| 309       | Wi-Fi             | 10.125.183.0/26       | 255.255.255.192       | 10.125.183.0 - 10.125.183.63          | 10.125.183.1 - 10.125.183.62          |

### Router Configuration ###

    interface FastEthernet 0/0.305
    encapsulation dot1Q 305
    ip address 10.125.183.190 255.255.255.192
    no shutdown
    interface FastEthernet 0/0.306
    encapsulation dot1Q 306
    ip address 10.125.183.126 255.255.255.192
    no shutdown
    interface FastEthernet 0/0.307
    encapsulation dot1Q 307
    ip address 10.125.182.254 255.255.255.0
    no shutdown
    interface FastEthernet 0/0.308
    encapsulation dot1Q 308
    ip address 10.125.183.222 255.255.255.224
    no shutdown
    interface FastEthernet 0/0.309
    encapsulation dot1Q 309
    ip address 10.125.183.62 255.255.255.192
    no shutdown

------------

    ex
    vlan database
    vlan 290 name B1F0
    vlan 291 name B1F1
    vlan 292 name B1DMZ
    vlan 293 name B1VoIP
    vlan 294 name B1WIFI
    vlan 295 name B2F0
    vlan 296 name B2F1
    vlan 297 name B2DMZ
    vlan 298 name B2VoIP
    vlan 299 name B2WIFI
    vlan 300 name B3F0
    vlan 301 name B3F1
    vlan 302 name B3DMZ
    vlan 303 name B3VoIP
    vlan 304 name B3WIFI
    vlan 305 name B4F0
    vlan 306 name B4F1
    vlan 307 name B4DMZ
    vlan 308 name B4VoIP
    vlan 309 name B4WIFI
    vlan 310 name B5F0
    vlan 311 name B5F1
    vlan 312 name B5DMZ
    vlan 313 name B5VoIP
    vlan 314 name B5WIFI
    vlan 315 name BackBone
