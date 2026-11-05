# Experiment 13: Domain Name System (DNS)

## 1. Aim

Configure a DNS server and clients so that the host name `www.lab.com` resolves to the configured web-server address, then verify name resolution.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- Simulated DNS server, switch, and multiple PCs.
- Copper Straight-Through cables, as specified in the report.
- Client command prompt and Packet Tracer Simulation Mode.

## 3. Theory

DNS maps domain/host names to IP addresses. A client sends a query to its configured DNS server; an A record provides an IPv4 address for a name. Once the client resolves the name, it can attempt to reach the returned address. DNS typically uses UDP for ordinary queries and can also use TCP. The supplied report's conclusion and learning-outcome material includes HTTP-oriented text that does not match its DNS procedure.

## 4. Network Topology

The report describes a DNS server, a switch, and PCs connected using Copper Straight-Through cables. It refers to a four-computer result and other computer-count variants, but does not consistently specify the total topology for every packet file. Diagrams are embedded in the DOCX/PDF; no standalone screenshots are present.

## 5. Configuration and Implementation

1. Connect the DNS server and PCs to the switch.
2. Assign addresses in the same network.
3. Enable DNS on the server and add the A record `www.lab.com` → `192.168.1.100`.
4. Configure client DNS server address as `192.168.1.10`.
5. Assign individual client IP addresses and test the name.

The report supplies the DNS server address and record destination above, but individual PC addresses and subnet masks are **Not specified in the provided practical files.** It does not clearly establish whether `192.168.1.100` belongs to a separately configured web server. The files are [`4computer.pkt`](./4computer.pkt), [`7comp.pkt`](./7comp.pkt), and [`12comp.pkt`).

## 6. Testing and Verification

The report specifies pinging the host name `www.lab.com`; the PDF also captions basic-diagram, simulation, and message-analysis figures. A successful name-based ping should demonstrate that the name is resolved and that the destination responds, but the report does not provide command output or a numeric ping transcript.

## 7. Results

The DNS procedure states that the host name resolves to `192.168.1.100`. The report also contains HTTP-oriented result/conclusion text, so only the DNS settings and test described above are treated as DNS evidence. The `.pkt` files have not been independently verified.

## 8. Learning Outcomes

- Explain DNS name-to-IPv4 resolution and the role of an A record.
- Configure a DNS service and client resolver address.
- Test name resolution by hostname.
- Identify inconsistencies between a procedure and unrelated report text.

