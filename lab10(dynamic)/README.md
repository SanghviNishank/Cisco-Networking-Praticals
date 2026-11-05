# Experiment 10: Dynamic Routing with RIP Version 2

## 1. Aim

Connect three router-based LANs and use RIP version 2 (RIPv2) to exchange routes dynamically, then verify end-to-end communication.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Three routers, three switches, and six PCs.
- Ethernet links for LANs and serial DCE/DTE links between routers.

## 3. Theory

RIP is a distance-vector routing protocol that uses hop count as its metric. A route with 15 hops is reachable; 16 represents infinity/unreachable. RIPv2 includes subnet-mask information and supports classless routing. Routers exchange routing information so they can learn remote networks without manually entering every remote route.

## 4. Network Topology

The report describes one switch and two PCs per router LAN, with Router 1 connected to Router 2 and Router 2 to Router 3 over serial links. Ethernet and serial DCE/DTE cabling are specified. The serial interfaces' exact names and topology beyond these links are not fully listed.

## 5. Configuration and Implementation

The DOCX provides these LAN interface and PC addresses, all with subnet mask `255.255.255.0`:

| LAN | Router LAN interface | PC addresses |
|---|---|---|
| Router 1 | G0/0: `192.168.10.1` | PC1: `192.168.10.2`; PC2: `192.168.10.3` |
| Router 2 | G0/0: `192.168.20.1` | PC3: `192.168.20.2`; PC4: `192.168.20.3` |
| Router 3 | G0/0: `192.168.30.1` | PC5: `192.168.30.2`; PC6: `192.168.30.3` |

The report instructs configuring unique IPs on the serial links, bringing interfaces up with `no shutdown`, setting a clock rate on the DCE end where required, and enabling RIPv2 to advertise the connected LAN and serial networks. The serial-link addresses/subnets and explicit PC default gateways are **Not specified in the provided practical files.** The source describes the configuration steps but does not include complete IOS command blocks, so exact `router rip` network statements are not reproduced here.

The Packet Tracer activity is [`dcnLab10.pkt`](./dcnLab10.pkt); its saved configuration has not been independently verified.

## 6. Testing and Verification

The report specifies `show ip route` and `show ip protocols` on routers, plus a ping from a PC on the Router 1 LAN to one on the Router 3 LAN. Given the documented PC6 address, the corresponding destination is `192.168.30.3` (from PC1: `ping 192.168.30.3`). Simulation Mode is also used to observe packet flow.

## 7. Results

The report concludes that end-to-end communication was verified using ping/ICMP and that routers learned routes dynamically. The report does not include serial-link addressing or command output; the result is its stated outcome rather than an independent run.

## 8. Learning Outcomes

- Configure a three-router topology with LAN and serial links.
- Explain RIPv2 route exchange and hop-count limitations.
- Interpret routing information with `show ip route` and `show ip protocols`.
- Test connectivity across multiple routed networks.

**Supporting practicals:** [`dcn lab 10 (1).docx`](./dcn%20lab%2010%20%281%29.docx) and [`dcn lab 10.pdf`](./dcn%20lab%2010.pdf).
