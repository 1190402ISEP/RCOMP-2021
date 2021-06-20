RCOMP 2020-2021 Project - Sprint 3 planning
===========================================
### Sprint master: 1191072 ###

# 1. Sprint's backlog #

|Task         | Task description|
|----|----|
|T.3.1|Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 1.|
|T.3.2|Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 2. Final integration of each member’s Packet Tracer simulation into a single simulation.|
|T.3.3|Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 3.|
|T.3.4|Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 4.|
|T.3.5|Update the campus.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 5.|

# 2. Technical decisions and coordination #

 * The OSPF area IDs to be used on each building (area id 0 is already assigned to the backbone network) end with its respective number.

 * VoIP phone numbers and prefix digits schema. Each building should have a different prefix digit, to configure calls forwarding to other buildings.

 * The DNS domain names to be used:

 The highest level domain should be the team’s repository
name: rcomp-20-21-dk-g1 - DNS root domain, created by member in charge of building 1.
Local DNS domain: building-X.rcomp-20-21-dk-g1, where X is the respective building number, to be created by the the other members of the team.

  All DNS servers should have the unqualified DNA name ns.

 * The IPv4 node address of the DNS name server of each DNS domain. The name of the domain’s
DNS name server has already been established to be ns within that domain.

building 1 - ns.rcomp-20-21-dk-g1

- 10.125.176.0

building 2 - ns.building-2.rcomp-20-21-dk-g1

- 10.125.178.0

building 3 - ns.building-3.rcomp-20-21-dk-g1

- 10.125.180.0

building 4 - ns.building-4.rcomp-20-21-dk-g1

- 10.125.182.0

building 5 - ns.building-5.rcomp-20-21-dk-g1

- 10.125.184.0

# 3. Subtasks assignment #

  * 1190402 - T.3.1
  * 1190742 - T.3.3
  * 1191045 - T.3.4
  * 1191072 - T.3.2
  * 1200587 - T.3.5
