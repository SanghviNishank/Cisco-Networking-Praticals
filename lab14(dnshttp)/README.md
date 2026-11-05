# Experiment 14: DNS and HTTP

## 1. Aim

The practical is titled as a combined DNS and HTTP experiment. However, the supplied procedure documents DNS configuration and name-resolution testing only; it does not explain an HTTP setup or browser test.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- One DNS server, one switch, and six PCs as described in the procedure.
- Copper Straight-Through cables.
- Packet Tracer Simulation Mode and client command prompt.

## 3. Theory

DNS translates a host name into an IP address using records such as an IPv4 A record. HTTP is an application-layer protocol through which a browser requests web content from a server. In a combined service exercise, DNS can resolve a web-server name and HTTP can deliver the page; the provided report does not specify that HTTP portion's service settings or test. The report's conclusion/learning outcomes also discuss TCP/UDP and a three-way handshake, which does not align clearly with its DNS-focused procedure.

## 4. Network Topology

The procedure specifies a DNS server, switch, and six PCs connected using Copper Straight-Through cables. The folder contains four Packet Tracer files, but filenames do not prove their saved device counts or configuration. Basic-diagram, simulation, and message-analysis figures are embedded in the DOCX/PDF; no standalone image files are present.

## 5. Configuration and Implementation

The documented DNS steps are:

1. Connect the DNS server and PCs to the switch.
2. Assign addresses in the same network.
3. Enable DNS and add the A record `www.lab.com` → `192.168.1.100`.
4. Configure client DNS address as `192.168.1.10`.
5. Test the host name and inspect the DNS exchange in Simulation Mode.

Individual PC addresses and subnet masks are **Not specified in the provided practical files.** Despite the combined aim, HTTP service enablement, web-page configuration, and browser access are also **Not specified in the provided practical files.** No IOS commands are described. Included files: [`4comp.pkt`](./4comp.pkt), [`4computer.pkt`](./4computer.pkt), [`7comp.pkt`](./7comp.pkt), and [`12comp.pkt`](./12comp.pkt).

## 6. Testing and Verification

The documented test is `ping www.lab.com`, with DNS packets observed in Simulation Mode. No HTTP URL/browser test, command output, or detailed expected packet trace is supplied. A ping test alone does not demonstrate that an HTTP page is served.

## 7. Results

The report presents DNS resolution/testing as the practical outcome. It does not provide evidence or configuration details sufficient to confirm an HTTP service test, despite the experiment title. The packet files have not been independently run.

## 8. Learning Outcomes

- Configure and test DNS name resolution with an A record.
- Observe DNS traffic in Packet Tracer Simulation Mode.
- Distinguish name resolution from delivery of an HTTP web page.
- Identify missing implementation details when a practical title and procedure differ.

**Supporting practicals:** [`LAB10.docx`](./LAB10.docx) and [`lab14.pdf`](./lab14.pdf).
