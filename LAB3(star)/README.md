# Experiment 3: Star Topology

## 1. Aim

Design and simulate star-topology networks and verify communication among their computers.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs and a central switch.
- PC-to-switch network links; cable type is not stated.

## 3. Theory

In a star topology, each endpoint has a link to a central device, commonly a switch. The switch forwards local Ethernet traffic between connected endpoints. A failed endpoint link generally affects that endpoint, while failure of the central switch can affect all attached devices. The supplied reports have blank theory sections but describe these central-device characteristics in the practical/results text.

## 4. Network Topology

The report describes a central switch with PCs connected around it and covers 6-, 16-, and 24-computer cases. The smallest practical has a naming mismatch: the report specifies 6 computers while the corresponding-looking file is named `5COMPUTER.pkt`. The packet contents are not independently checked. Figures are embedded in the supplied DOCX/PDF; there are no standalone screenshot files.

## 5. Configuration and Implementation

1. Place a central switch and the PCs in Packet Tracer.
2. Connect every PC to the central switch.
3. Configure each PC with a unique static IP address in the same network.
4. Allow the switch/network to stabilize before testing communication.

Specific IP addresses, subnet masks, switch model, port mapping, and IOS commands are not specified in the provided practical files. Available practicals: [`5COMPUTER.pkt`](./5COMPUTER.pkt), [`16COM.pkt`](./16COM.pkt), and [`24COMPUTERS.pkt`](./24COMPUTERS.pkt).

## 6. Testing and Verification

The procedure calls for message transmission in Simulation Mode and inspection of message-received analysis. The report describes disconnecting one computer while the remaining network continues to operate; it identifies central-switch failure as a possible cause of broader failure, not as a reported test. No exact test command or output is supplied.

## 7. Results

The reports claim successful communication among connected computers. The stated endpoint-disconnection behavior is consistent with the described star arrangement. The `.pkt` files have not been independently run.

## 8. Learning Outcomes

- Identify the central-device structure of a star topology.
- Connect and address multiple PCs through a switch.
- Use Simulation Mode to inspect message delivery.
- Understand the distinction between an endpoint-link failure and central-switch failure.

