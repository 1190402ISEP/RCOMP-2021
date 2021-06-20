RCOMP 2020-2021 Project - Sprint 2 planning
===========================================
### Sprint master: 1200587 ###

# 1. Sprint's backlog #

|Task         | Task description|
|--------------|--------------------------------|
|T.2.1|Development ofa layer two and layer three Packet Tracer simulation for building 1, and also encompassing the campus backbone. Integration of everymembers’ Packet Tracer simulationsinto a single simulation.|
|T.2.2|Development of a layer two and layer three Packet Tracer simulation forbuilding 2, and also encompassing the campus backbone.|
|T.2.3|Development of a layer two and layer three Packet Tracer simulation for building 3, and also encompassing the campus backbone.|
|T.2.4|Development of a layer two and layer three Packet Tracer simulation for building 4, and also encompassing the campus backbone.|
|T.2.5|Development of a layer two and layer three Packet Tracer simulation for building 5, and also encompassing the campus backbone.|



# 2. Technical decisions and coordination #

*Work under the same definitions from sprint 1.
*Delivery method: Simulation file from Cisco Packet Tracer with the name buildingX.pkt where X represents the building.
*Everyone must export the configuration file from the switches and the router.
*Devices names should be meaningful and easy to understand.
*All simulations must be united into a single file named campus.pkt.
*Everyone must write in a README.md file all the addresses and networks defined for each VLAN for each building.

## VLAN Distribution ##

*VTP Domain Name : rcompdkg1
  *VLANIDs: 290-320
    * : Building 1 -> 290 - 294
    * : Building 2 -> 295 - 299
    * : Building 3 -> 300 - 304
    * : Building 4 -> 305 - 309
    * : Building 5 -> 310 - 314
    * : Backbone VLAN -> 315 

#### IPv4 address blocks

Na pasta de cada elemento do grupo estão representados os IPv4 respetivos.

ISP - 120.57.101.233/30


#### Wifi channels ####

 1 | 6 | 11


#### Backbone cable types to be used ####

CAT7
Fibra monomodo
Fibra multimodo



# 3. Subtasks assignment #
  * 1190402 - T.2.1
  * 1190742 - T.2.3
  * 1191045 - T.2.4
  * 1191072 - T.2.2
  * 1200587 - T.2.5

