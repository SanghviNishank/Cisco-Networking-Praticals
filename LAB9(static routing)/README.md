# Experiment 9: Static Routing

## 1. Aim

Configure static routing between two routers so that devices on separate LANs can communicate.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs, switches, and two routers.
- LAN links and an inter-router link.

## 3. Theory

Routers forward packets between IP networks using routing tables. A static route is entered manually and identifies a destination network and a next hop or exit interface. Static routes are predictable and do not require a routing update protocol, but an administrator must update them when the topology changes. Each end host also needs a correct IP address, subnet mask, and default gateway to reach remote networks.

## 4. Network Topology

The report describes PCs connected to switches, each switch connected to a router, and the two routers interconnected. It includes 6-, 14-, and 24-computer variants. The exact number of PCs per LAN, router models/interfaces, and inter-router link type are not specified in the text. Figures are embedded in the DOCX/PDF; no standalone images are supplied.

## 5. Configuration and Implementation

1. Create the two LANs and connect each to its router.
2. Connect the routers and assign host addresses and default gateways.
3. Configure static routes so each router has a path to the remote LAN.
4. Save the Packet Tracer activity.

Specific IP addresses, masks, gateway values, route destinations, next hops, interface names, and IOS commands are **Not specified in the provided practical files.** Do not infer a command line from the topology description. Practical files: [`6COMP.pkt`](./6COMP.pkt), [`14comp.pkt`](./14comp.pkt), and [`24comp.pkt`](./24comp.pkt).

## 6. Testing and Verification

The report says hosts in different subnetworks communicated through the two routers and that packet-level analysis confirmed forwarding. It does not provide exact test addresses, ping output, or router verification commands.

## 7. Results

The reports describe successful inter-subnet communication after configuring the routing path. The result is a reported outcome; the `.pkt` files have not been independently run or inspected for their saved routes.

## 8. Learning Outcomes

- Explain the purpose and limitations of static routes.
- Connect separate LANs through routers.
- Configure hosts and gateways for remote-network access.
- Verify forwarding between subnets using packet analysis.


