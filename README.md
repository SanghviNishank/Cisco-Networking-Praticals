# Data Communication and Networking (DCN) Lab

## Project overview

This repository contains 14 Cisco Packet Tracer lab experiments for Data Communication and Networking. Each experiment folder includes one or more `.pkt` practical files and, where provided, a lab report in DOCX or PDF format. The experiment READMEs document the practical as described by its accompanying materials; they do not claim that packet-file configurations were independently opened or tested.

## Objectives

- Design and simulate common computer-network topologies.
- Configure and observe LAN, MAN, server, name-resolution, web, Bluetooth, and routing scenarios.
- Practice addressing, connectivity checks, and Packet Tracer Simulation Mode.
- Relate network diagrams and practical configurations to the underlying protocols and concepts.

## Software and tools

- Cisco Packet Tracer (the supplied reports do not specify a version).
- Simulated PCs, switches, routers, servers, Bluetooth speakers, and a portable music player as described in the relevant experiment.
- DOCX/PDF lab reports supplied with the practicals.

## Technologies and concepts covered

Mesh, ring, star, bus, and hybrid topologies; switched LANs and MANs; static IPv4 addressing; DNS and A records; HTTP client-server access; Bluetooth discovery and pairing; static routing; RIP version 2; and Packet Tracer Simulation Mode.

## Experiments

| No. | Experiment | Summary | Practical folder and README |
|---:|---|---|---|
| 1 | Mesh topology | Simulates mesh-style switched networks at several computer counts and describes alternate paths. | [LAB1(mesh)](./LAB1%28mesh%29/README.md) |
| 2 | Ring topology | Simulates ring-topology networks and reports communication/failure behavior for multiple sizes. | [LAB2(ring)](./LAB2%28ring%29/README.md) |
| 3 | Star topology | Builds star networks around a central switch and checks message delivery. | [LAB3(star)](./LAB3%28star%29/README.md) |
| 4 | Bus topology | Simulates a bus/backbone arrangement and reports ping and link-failure observations. | [LAB4(bus)](./LAB4%28bus%29/README.md) |
| 5 | Hybrid topology | Describes BUS+STAR, RING+STAR, and BUS+RING arrangements at different sizes. | [LAB5(hybrid)](./LAB5%28hybrid%29/README.md) |
| 6 | DNS | Uses a DNS server and clients to demonstrate name-based access; numeric DNS settings are not given in the report. | [LAB6(DNS)](./LAB6%28DNS%29/README.md) |
| 7 | LAN | Builds switched local networks with clients and a server; the objective and procedure differ on router use. | [LAB7(LAN)](./LAB7%28LAN%29/README.md) |
| 8 | MAN / inter-network routing | Covers router-connected networks; the PDF frames it as a MAN while the DOCX objective describes static routing. | [LAB8(MAN)](./LAB8%28MAN%29/README.md) |
| 9 | Static routing | Describes two routers joining separate LANs using manually configured routes. | [LAB9(static routing)](./LAB9%28static%20routing%29/README.md) |
| 10 | Dynamic routing (RIP) | Connects three router-based LANs and describes RIP v2 with a documented LAN addressing table. | [lab10(dynamic)](./lab10%28dynamic%29/README.md) |
| 11 | Bluetooth | Pairs a portable music player with Bluetooth speaker(s) and checks playback. | [lab11(Bluetooth)](./lab11%28Bluetooth%29/README.md) |
| 12 | HTTP | Enables HTTP on a server and accesses its page from a client browser. | [lab12(http)](./lab12%28http%29/README.md) |
| 13 | DNS | Configures `www.lab.com` to resolve to `192.168.1.100` and tests name resolution. | [LAB13(dns)](./LAB13%28dns%29/README.md) |
| 14 | DNS and HTTP | The materials describe DNS configuration and simulation; the HTTP portion named in the aim is not documented in the procedure. | [lab14(dnshttp)](./lab14%28dnshttp%29/README.md) |

## Project structure

Existing folder names and practical resources are retained. `.pkt` files are listed by their supplied names; the filenames do not independently confirm each file's saved topology or settings.

```text
dcnlab/
├── README.md
├── LAB1(mesh)/                 
├── LAB2(ring)/               
├── LAB3(star)/                
├── LAB4(bus)/                 
├── LAB5(hybrid)/               
├── LAB6(DNS)/                 
├── LAB7(LAN)/                  
├── LAB8(MAN)/               
├── LAB9(static routing)/      
├── lab10(dynamic)/            
├── lab11(Bluetooth)/          
├── lab12(http)/               
├── LAB13(dns)/                 
└── lab14(dnshttp)/             
```

The original documents contain embedded figures, but the experiment folders do not contain standalone screenshot or diagram files. Their individual READMEs link to the supplied source reports where available.

## Opening and running a practical

1. Install or open Cisco Packet Tracer.
2. Open the required `.pkt` file from its experiment folder using **File → Open** (or the equivalent open command in your Packet Tracer version).
3. Inspect the saved topology and device settings before running the activity. The experiment README and the accompanying report explain what the report specifies; consult the `.pkt` file for its actual saved state.
4. Use **Realtime** mode for ordinary interaction or **Simulation** mode to inspect packet/event flow when the practical calls for it.
5. Repeat only the tests applicable to the experiment, such as a browser request, a ping, or the documented router show commands. Exact settings omitted by the reports should be read from the opened practical rather than guessed.


## Conclusion

The project brings together topology design, application services, wireless device pairing, and routing exercises in Packet Tracer. The per-experiment documentation is grounded in the supplied reports and artifacts; where source materials conflict or omit values, that limitation is stated rather than replaced with assumed configuration.
