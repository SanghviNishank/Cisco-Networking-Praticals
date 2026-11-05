# Experiment 12: HTTP Web Access

## 1. Aim

Enable the HTTP service on a Packet Tracer server and access its web page from a client computer.

## 2. Software and Tools Required

- Cisco Packet Tracer (version not specified).
- One server, one PC, and one switch, as specified by the procedure.
- Server HTTP service and the PC's web browser.

## 3. Theory

HTTP is an application-layer protocol used by clients to request web resources from a server. A browser sends a request to the server and displays the returned page. The client must be able to reach the server at the configured address, and the server's HTTP service must be enabled. The report does not specify a particular HTTP version or port setting.

## 4. Network Topology

The procedure describes one server and one PC connected through one switch. The result section instead says “With 6 computers” and includes basic-diagram, simulation, and message-analysis captions. This conflicts with the one-PC procedure; the exact topology in each `.pkt` file is not established by its filename. Figures are embedded in the DOCX/PDF reports; no standalone images are supplied.

## 5. Configuration and Implementation

1. Place the server, PC, and switch and connect them with network cables.
2. Assign server and client addresses in the same network.
3. Enable HTTP on the server and create or verify the web page.
4. From the PC browser, enter the server's IP address.

Numeric IP addresses, subnet mask, cable type, page contents, and any IOS configuration are **Not specified in the provided practical files.** Practical files: [`4computer.pkt`](./4computer.pkt), [`7comp.pkt`](./7comp.pkt), and [`12comp.pkt`). Their saved topologies are not independently confirmed.

## 6. Testing and Verification

The stated test is opening the server's IP address in the client browser and confirming that the page loads. No exact URL/address or command output is given. The source also includes simulation/message-analysis figures.

## 7. Results

The procedure's success criterion is a page successfully displayed in the PC browser. The report's result section refers to six computers, which is inconsistent with its one-PC procedure. The `.pkt` files have not been independently run.

## 8. Learning Outcomes

- Explain HTTP's client-server request/response role.
- Enable a server application service in Packet Tracer.
- Configure same-network client/server addressing.
- Verify an application service using a web browser.

**Supporting practicals:** [`lab12.docx`](./lab12.docx), [`LAB12.pdf`](./LAB12.pdf), and [`LAB11.pdf`](./LAB11.pdf). `LAB11.pdf` also describes HTTP but labels the report as Experiment 10.
