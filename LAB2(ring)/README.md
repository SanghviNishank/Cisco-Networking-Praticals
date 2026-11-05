# Experiment 2: Ring Topology

## 1. Aim

Construct and simulate ring-topology networks of 6, 16, and 24 computers and observe communication, including the report's stated alternate-path/failure behavior.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs and switches.
- Network links between PCs and switches and inter-switch links.

## 3. Theory

In a ring topology, each node or network segment is connected to neighboring elements in a closed path. Data follows links around the ring; an alternate route can help preserve communication after a failure when the design and forwarding behavior support it. The theory section in both supplied reports is blank, and no ring-control or recovery protocol is identified. Ethernet switching loops and their prevention are not described in the practical.

## 4. Network Topology

The reports identify 6-, 16-, and 24-computer ring cases built with PCs and switches. The detailed connection layout, switch models, cable types, and port assignments are not specified in the provided practical files. Figures for basic diagrams, simulation, and message analysis are embedded in the DOCX/PDF reports; no separate image files are supplied.

## 5. Configuration and Implementation

1. Place the PCs and switches for the selected size.
2. Connect the devices in the ring arrangement shown in the practical.
3. Assign static IP addresses to the PCs within the same network.
4. Allow the network to stabilize before sending test messages.

Specific addresses, subnet masks, switch models, and IOS commands are not specified in the provided practical files. Packet Tracer files: [`6COMPUTERS.pkt`](./6COMPUTERS.pkt), [`16COM.pkt`](./16COM.pkt), and [`24COMPUTERS.pkt`](./24COMPUTERS.pkt). Their saved configurations are not independently confirmed.

## 6. Testing and Verification

The procedure describes testing message transmission in Simulation Mode. The results additionally claim that communication continued after a single link or node failure, but the exact failure scenario and test output are not provided. No specific command syntax is given.

## 7. Results

The reports state that the computers communicated and that the described single-failure test did not interrupt transmission. These are reported results, not an independent execution of the supplied `.pkt` files.

## 8. Learning Outcomes

- Recognize the arrangement and trade-offs of a ring topology.
- Build a switched topology and configure same-network static addressing.
- Observe packet/message movement in Simulation Mode.
- Relate a network failure to the availability of alternate paths.


