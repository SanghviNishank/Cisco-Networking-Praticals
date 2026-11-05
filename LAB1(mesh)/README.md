# Experiment 1: Mesh Topology

## 1. Aim

Design and simulate mesh-style computer networks with 5, 16, and 24 computers, and examine communication and the availability of alternate paths as described in the lab report.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs and switches.
- Ethernet links between PCs and switches and between switches, as described in the procedure.

## 3. Theory

A mesh topology connects network nodes through multiple links, so communication may have an alternate path when a link is unavailable. Switches forward frames toward the destination on a local Ethernet network. The report lists reliability and fault tolerance as benefits and increased cabling, cost, and management complexity as drawbacks. The report does not establish whether the practical is a full or partial mesh, nor does it identify a redundancy protocol.

## 4. Network Topology

The report describes PCs connected to switches, with switches interconnected to provide an alternate path. It discusses 5-, 16-, and 24-computer cases. Device models, exact switch count, port mapping, and cable types are not specified in the provided practical files. Nine figures are embedded in `LAB1.docx`; no standalone screenshot files are present.

## 5. Configuration and Implementation

1. Place the required number of PCs and switches in Packet Tracer.
2. Connect each PC to a switch and interconnect the switches as represented by the practical.
3. Assign unique static IP addresses to the PCs within the same network.
4. Allow the switched network to stabilize before testing.

Specific IP addresses, subnet masks, switch models, and IOS commands are not specified in the provided practical files. The folder contains [`5COMPUTERS.pkt`](./5COMPUTERS.pkt), [`16COM.pkt`](./16COM.pkt), and [`24COMPUTERS.pkt`](./24COMPUTERS.pkt); their internal configurations are not independently confirmed here.

## 6. Testing and Verification

The report calls for sending messages in Simulation Mode and observing successful delivery/message analysis. It does not provide specific ping commands or detailed output. The report recommends allowing time for the network to stabilize before testing.

## 7. Results

The report states that communication between the computers completed successfully and that messages were delivered. This is the documented outcome; the saved Packet Tracer files have not been independently run or verified.

## 8. Learning Outcomes

- Understand mesh-style connectivity and alternate paths.
- Connect PCs and switches in Packet Tracer.
- Apply static addressing to devices on a local network.
- Inspect message delivery in Simulation Mode.

**Supporting practical:** [`LAB1.docx`](./LAB1.docx).
