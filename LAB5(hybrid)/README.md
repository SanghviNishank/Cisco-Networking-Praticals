# Experiment 5: Hybrid Topology

## 1. Aim

Build and simulate hybrid networks that combine different topology types, and observe communication across the combined layout.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs and switches.
- Network links between endpoints and switches and between switch sections.

## 3. Theory

A hybrid topology combines two or more basic topologies to meet a network's layout or connectivity needs. The practical names three combinations: BUS+STAR for 14 computers, RING+STAR for 16, and BUS+RING for 24. A hybrid design inherits properties and limitations from its component topologies. The report discusses flexibility and scalability as benefits and added design/management complexity as drawbacks.

## 4. Network Topology

The report's practical section identifies BUS+STAR (14 computers), RING+STAR (16), and BUS+RING (24). It describes PCs, switches, and interconnected switch sections. Its conclusion generalizes the design as multiple star networks, so the exact layout should be read from the embedded figures or opened `.pkt` file. No standalone screenshot or diagram files are supplied; figures are embedded in the DOCX/PDF.

## 5. Configuration and Implementation

1. Select the topology combination and computer count.
2. Place PCs and switches and connect them according to the corresponding practical diagram.
3. Assign unique static IP addresses within the same network, as described by the report.
4. Allow the network to stabilize before testing message delivery.

Numeric IP addresses, subnet masks, device models, port assignments, and IOS commands are not specified in the provided practical files. Packet Tracer files: [`14COMPUTER.pkt`](./14COMPUTER.pkt), [`16COM.pkt`](./16COM.pkt), and [`24COMPUTERS.pkt`](./24COMPUTERS.pkt). The mapping from individual file to topology variant is not confirmed by the filenames alone.

## 6. Testing and Verification

The report describes ping testing and message analysis in Simulation Mode. It states that communication succeeded and discusses alternate paths in the ring-based section and a backbone in bus-based sections. No command output or detailed failure test is supplied.

## 7. Results

The report claims successful communication for the hybrid practicals. The details of each saved packet file are not independently verified.

## 8. Learning Outcomes

- Explain how basic topologies can be combined.
- Build a multi-section switched network in Packet Tracer.
- Configure static addressing and observe end-to-end traffic.
- Compare flexibility with the added complexity of a hybrid layout.

**Supporting practicals:** [`LAB5.docx`](./LAB5.docx) and [`lab5.pdf`](./lab5.pdf).
