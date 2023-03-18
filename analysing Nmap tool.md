1)Explain the subnet and use the NMAP Command to scan the services for the whole subnet.
 
SUBNETTING:
 
When a bigger network is divided into smaller networks is known as Subnetting. In subnetting , IP address can be alloted as per the number of host so there is no wastage of IP address.the system within subnet can communicate with each other,but the system in different subnets cannot with each other.so the subnetting is considered secure. 

Nmap scanning of whole services :
 
Nmap is used to scan the networks ,to know the active host ,numberts of ports open ,detailed information of IP's activated in the network .since nmap is used to scan within spefific range of IP address.

2) What is a firewall and mention its types. Use the NMAP command to detect that a firewall protects  the host.

FIREWALL:

Firewalls prevent unauthorized access to networks through software or firmware.It will filters the incoming and outgoing traffic within a private network, according to a set of rules to  prevent cyberattacks. 

TYPES OF FIREWALL:

Packet-filtering Firewalls:

It will monitor network traffic and filters incoming packets based on configured security rules. These firewalls are designed to block network traffic IP protocols, an IP address, and a port number if a data packet does not match the established rule-set.It will not prevent web-based attacks.

Circuit-level Gateways:

This will operate at  session level  of the OSI model by verifying TCP  connections and sessions.it will  not prevent malicious data which contains perfect tcp connection.

Proxy Firewalls:

Proxy firewalls operate at the application layer as an intermediate device to filter incoming traffic between two end systems.Once the connection is established, the proxy firewall inspects data packets coming from the source. If the contents of the incoming data packet are protected, the proxy firewall transfers it to the client. 

Stateful Multi-layer Inspection Firewalls:

when a user establishes a connection and requests data, the SMLI firewall creates a database.The database is used to store session information such as source IP address, port number, destination IP address, destination port number, etc. Connection information is stored for each session in the state table.This will  create  security rules to allow anticipated traffic.

Next-generation Firewalls :

This firewall will contain the features of other firewall and functionalities of other firewall.

Network Address Translation  Firewalls:

IT is used to access internet traffic  and block all unwanted connections.NAT firewalls create a unique IP address and hide individual devices' IP addresses.

cloud firewall:

Cloud firewalls are typically maintained and run on the Internet by third-party vendors. This type of firewall is considered similar to a proxy firewall. 

3)Use the NMAP command to scan a network and determine which devices are up and running.

4) What are vertical and horizontal scanning?

VERTICAL SCANNING:

The vertical scan is a port scan that targetsseveral destination ports on a single host. it can be  described as a single IP being scanned for multiple ports.

HORIZONTAL SCANNING:

A horizontal scan is a port scan that targets same port on several hosts.It can be described as scan against a group of IPs for a single port.

h) Explain ping sweeping and Perform ping sweeping using Nmap

The Ping sweep is a starting point of discovery. it is a information gathering technique used  to find the live host by pinging them.One host like the user requests data and the receiver host accepts it, sends back packets of information in bytes.

1) What is a web application firewall? How do you use Nmap to detect a WAF? Perform WAF fingerprint detection using NMAP.

A web application firewall is designed to protect web apps by filtering, monitoring, and blocking any malicious incoming HTTP traffic while also preventing unauthorized data from leaving the application.

2) What is EXIF data? Try to find EXIF data of images on a website using NMAP NSE.

EXIF stands for Exchangeable Image File Format. This data is in every image file a camera records.it contains metadata of the photo.






