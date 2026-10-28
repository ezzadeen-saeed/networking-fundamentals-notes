# Network Security: Ports and Firewalls

## 1. What Is a Port?
A port is a logical number used by transport protocols such as TCP and UDP to direct network traffic to the appropriate service or application.

Examples of commonly used ports:
- TCP 22: SSH remote administration
- TCP/UDP 53: DNS, depending on the query and operation
- TCP 80: HTTP
- TCP 443: HTTPS commonly uses TLS over TCP

Port numbers alone do not prove which service is running or whether a system is vulnerable.

## 2. What Is a Firewall?
A firewall enforces rules that control network traffic according to its configuration and capabilities. Rules can consider factors such as source, destination, protocol, port, and connection state.

## 3. Example Policy for a Web Server
- Permit inbound TCP 443 when required for HTTPS.
- Restrict SSH access to trusted administrative sources.
- Deny other unsolicited inbound traffic by default where appropriate.

Rules must be tested to avoid blocking required services.

## 4. Firewall Types
- Host-based firewall: protects an individual system.
- Network firewall: controls traffic between networks or security zones.
- Web Application Firewall (WAF): inspects HTTP application traffic for certain attack patterns.

## 5. Attack Surface
The attack surface includes exposed services, interfaces, and entry points that may be targeted. Disabling unnecessary services and restricting access can reduce exposure.

## 6. Defensive Review Questions
1. Which service is listening on each exposed port?
2. Is the service necessary?
3. Which sources need access?
4. Is the software supported and securely configured?
5. Are relevant events logged and reviewed?

## Learning Status
Introductory study notes. Practical observations will be added after testing in an authorized lab.
