# Experiment 7: Local Area Network (LAN)

## 1. Aim

Design a local network in Packet Tracer and verify communication between client computers and a server.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs, switches, and a server.
- A router is mentioned in the objective, but its use is not consistent across the report.

## 3. Theory

A Local Area Network (LAN) connects devices within a limited local area. Ethernet switches forward frames among devices on the LAN. A server can provide a service to client PCs; clients can reach it by its IP address when they share a network or have a valid route. A default gateway is needed when traffic must leave the local subnet. The report discusses centralized management and configuration/security considerations.

## 4. Network Topology

The report describes 6-, 14-, and 24-computer variants, with PCs grouped on a switch and a server connected to a switch. The objective mentions PCs, switches, and routers, while the procedure and conclusion describe a switched LAN and say to leave the gateway empty when no router is used. Whether the packet includes a router is therefore not established by the text. Figures are embedded in the reports, not supplied as standalone images.

## 5. Configuration and Implementation

1. Place PCs, switches, and the server for the selected variant.
2. Connect the devices as represented by the practical.
3. Assign static IP and DNS settings to PCs and a static IP to the server.
4. Leave the default gateway empty only for the no-router, same-subnet setup described in the report.

Exact addresses, subnet masks, DNS values, router configuration, and server service settings are **Not specified in the provided practical files.** Available files: [`6COMP.pkt`](./6COMP.pkt), [`14comp.pkt`](./14comp.pkt), and [`24comp.pkt`](./24comp.pkt).

## 6. Testing and Verification

The report describes accessing the server from client browsers or command prompts using its IP address and states that communication succeeded. It does not give a specific address, URL, command, or output. Inspect the opened practical for the actual saved settings.

## 7. Results

The report claims successful client access to the server. Its router-related objective and router-free procedure are inconsistent, so the exact routing scope should be confirmed in the `.pkt` file.

## 8. Learning Outcomes

- Distinguish a LAN from communication that requires routing.
- Connect and address PCs and servers through switches.
- Understand the role of a default gateway.
- Verify client-server access using the method configured in the practical.

**Supporting practicals:** [`LAB7.docx`](./LAB7.docx) and [`lab7.pdf`](./lab7.pdf).
