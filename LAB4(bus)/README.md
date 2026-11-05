# Experiment 4: Bus Topology

## 1. Aim

Simulate a bus-topology network at the computer counts described in the report and observe communication over the shared backbone.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs and network devices/links shown in the practical.
- The report describes PCs, switches, and a single backbone cable.

## 3. Theory

A bus topology uses a shared backbone to which network nodes or segments attach. A fault affecting an individual endpoint link may leave other nodes connected, whereas a break in the shared backbone can disrupt communication across the bus. The report identifies the backbone as a single point of failure. Its wording also mentions switch interconnections, so the exact physical realization should be checked in Packet Tracer rather than inferred from the topology name alone.

## 4. Network Topology

The report describes cases with 6, 16, and 24 computers and refers to a single backbone cable. It also describes PCs connected through switches. The smallest-case packet is named `5COMPUTER.pkt`, although the text says 6 computers. Exact device models, port mapping, and cable details are not specified. Practical figures are embedded in the DOCX/PDF; no separate image files are present.

## 5. Configuration and Implementation

1. Place the PCs and the network devices used by the selected practical.
2. Connect the devices in the bus/backbone arrangement shown in the source report.
3. Assign each PC a unique static IP address in the same network.
4. Wait for the network to stabilize before testing.

Specific IP addresses, subnet masks, device models, and IOS commands are not specified in the provided practical files. Available files: [`5COMPUTER.pkt`](./5COMPUTER.pkt), [`16COM.pkt`](./16COM.pkt), and [`24COMPUTERS.pkt`](./24COMPUTERS.pkt).

## 6. Testing and Verification

The report says communication was checked with ping tests and Simulation Mode. It reports that disconnecting one computer did not disrupt the rest of the network, while a backbone failure breaks communication. No ping addresses or detailed output are given.

## 7. Results

The practical report claims successful communication and describes the expected distinction between an individual-computer disconnection and a backbone failure. This outcome is reported in the supplied material; the `.pkt` files have not been independently tested.

## 8. Learning Outcomes

- Describe the shared-backbone concept and its failure implications.
- Configure same-network static addressing for a simulated LAN.
- Verify connectivity with ping and Packet Tracer Simulation Mode.
- Relate topology structure to the scope of a link failure.


