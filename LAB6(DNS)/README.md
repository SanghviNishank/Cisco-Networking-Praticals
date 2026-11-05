# Experiment 6: Domain Name System (DNS)

## 1. Aim

Create a network with a DNS server and client computers, then demonstrate name-based access to a network resource.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated PCs, a server, and switches.
- Client browser and Packet Tracer Simulation Mode, as described in the report.

## 3. Theory

The Domain Name System (DNS) resolves human-readable domain names to IP addresses so clients can use names rather than remember numeric addresses. A client sends a lookup request to a configured DNS server and uses the returned address to reach the destination. DNS commonly uses UDP and can also use TCP, depending on the operation. The report discusses the convenience of name-based access and risks such as spoofing or poisoning.

## 4. Network Topology

The report describes PCs grouped on switches and a server connected to a switch. It mentions variants with 6, 16, and 24 computers. Exact device models, links between switches, domain name, and server placement are not fully specified in the provided practical files. Figures are embedded in the DOCX/PDF; no standalone images are present.

## 5. Configuration and Implementation

1. Place the PCs, server, and switches for the selected computer-count variant.
2. Connect the devices as shown in the practical.
3. Assign static IP and DNS settings to clients and a static IP to the server.
4. Configure the DNS service and name data as intended by the practical.

The specific IP addresses, subnet masks, DNS server address, domain name, and DNS record values are **Not specified in the provided practical files.** Do not substitute values from another DNS experiment. Available practicals: [`6comp.pkt`](./6comp.pkt), [`16comp.pkt`](./16comp.pkt), and [`24comp.pkt`](./24comp.pkt); their configurations are not independently confirmed.

## 6. Testing and Verification

The report says to access a resource by its domain name in a client browser and inspect packet exchange in Simulation Mode. It reports successful resolution but gives no exact domain, command, or captured output.

## 7. Results

The report states that the domain name resolved to its corresponding IP address and that the simulation completed successfully. These are the source report's claims; the `.pkt` files have not been independently run.

## 8. Learning Outcomes

- Explain the purpose of DNS name resolution.
- Configure a simulated DNS client/server network.
- Observe DNS-related packet exchange in Simulation Mode.
- Recognize why numeric service settings must be confirmed from the actual practical.

