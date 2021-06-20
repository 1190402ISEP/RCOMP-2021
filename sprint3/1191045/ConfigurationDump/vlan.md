en
config t
interface vlan 305
ip address 10.125.183.128 255.255.255.192
interface vlan 306
ip address 10.125.183.64 255.255.255.192
interface vlan 307
ip address 10.125.182.0 255.255.255.0
interface vlan 308
ip address 10.125.183.192 255.255.255.224
interface vlan 309
ip address 10.125.183.0 255.255.255.192

ex
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
