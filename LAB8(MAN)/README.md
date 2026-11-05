# Experiment 8: Metropolitan Area Network (MAN) / Inter-Network Routing

## 1. Aim

The supplied materials do not state a single consistent aim: the PDF presents the practical as designing a Metropolitan Area Network (MAN), while the DOCX objective describes static routing between two routers. This README records the shared router-connected-network implementation without assuming which framing is definitive.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs, switches, and routers.
- Links between each local network and its router, and between routers.

## 3. Theory

A MAN connects multiple LANs across a metropolitan area; routers forward traffic between IP networks. Static routing uses manually configured destination routes and next hops and is predictable, but routes require manual maintenance as networks change. The supplied DOCX discusses static routing; the PDF emphasizes MAN connectivity. The exact routing protocol/configuration used in this experiment is not consistently documented.

## 4. Network Topology

The reports describe PCs connected through switches to routers, with routers interconnected. The DOCX mentions variants with 6, 14, and 24 computers. The PDF describes LANs connected through routers/WAN links. Exact router count, WAN technology, device models, and link addressing are not consistently specified. Figures are embedded in the DOCX/PDF; no standalone image files are present.

## 5. Configuration and Implementation

1. Place the LAN PCs, switches, and routers for the selected practical.
2. Connect each LAN to its router and interconnect the routers as shown.
3. Assign static IP addresses to PCs and configure the appropriate default gateways.
4. Configure inter-network routing according to the practical's intended routing setup.

Numeric IP addresses, subnet masks, gateway values, WAN-link addresses, route destinations/next hops, and IOS commands are **Not specified in the provided practical files.** The conflicting aim also prevents confirming whether the intended configuration is specifically static routing. Practical files: [`6COMP.pkt`](./6COMP.pkt), [`14comp.pkt`](./14comp.pkt), and [`24comp.pkt`](./24comp.pkt).

## 6. Testing and Verification

The reports state that communication between different network segments was tested and succeeded. They do not provide exact ping commands, router show-command output, or numeric test endpoints.

## 7. Results

The reports claim successful inter-network communication through router configuration. The PDF and DOCX disagree on whether the emphasis is a MAN or static routing; inspect the saved Packet Tracer topology and settings for the precise implementation.

## 8. Learning Outcomes

- Understand how routers connect distinct LANs.
- Distinguish a MAN context from a particular routing mechanism.
- Configure host addressing and default gateways in a routed topology.
- Identify why complete route and WAN addressing details matter for reproducibility.


