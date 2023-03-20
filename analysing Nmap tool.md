                             ANALYSING Nmap tool

 name:karthika p
 
 roll no: cb.en.p2cys22001


a)Explain the subnet and use the NMAP Command to scan the services for the whole subnet.
 
SUBNETTING:
 
When a bigger network is divided into smaller networks is known as Subnetting. In subnetting , IP address can be alloted as per the number of host so there is no wastage of IP address.the system within subnet can communicate with each other,but the system in different subnets cannot with each other.so the subnetting is considered secure. 

Nmap scanning of whole services :
 
Nmap is used to scan the networks ,to know the active host ,numberts of ports open ,detailed information of IP's activated in the network .since nmap is used to scan within spefific range of IP address.

![image](https://user-images.githubusercontent.com/122804908/226361305-7205825e-bc72-47fa-bf0a-4c8cbcc0661a.png)


b) What is a firewall and mention its types. Use the NMAP command to detect that a firewall protects  the host.

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

Nmap is used to find out whether the host is protected by firewall or not

![image](https://user-images.githubusercontent.com/122804908/226339023-ca5e478a-0980-45dc-b6c8-69b706dfccfd.png)


c)Use the NMAP command to scan a network and determine which devices are up and running.

![image](https://user-images.githubusercontent.com/122804908/226363367-9fef3992-c5ab-41fe-8f37-05f0172b2f62.png)


d) What are vertical and horizontal scanning?

VERTICAL SCANNING:

The vertical scan is a port scan that targetsseveral destination ports on a single host. it can be  described as a single IP being scanned for multiple ports.

HORIZONTAL SCANNING:

A horizontal scan is a port scan that targets same port on several hosts.It can be described as scan against a group of IPs for a single port.

h) Explain ping sweeping and Perform ping sweeping using Nmap

The Ping sweep is a starting point of discovery. it is a information gathering technique used  to find the live host by pinging them.One host like the user requests data and the receiver host accepts it, sends back packets of information in bytes.

![image](https://user-images.githubusercontent.com/122804908/226365706-ff43dbfe-2cb9-4b03-89ae-e99fba2c94f9.png)


f)f) Use NMAP commands to export the output in XML format

![image](https://user-images.githubusercontent.com/122804908/226339866-f3eada99-f377-4fd0-8d8d-db8e0333e48f.png)


g) Use the NMAP command to get OS information about a host. 

![image](https://user-images.githubusercontent.com/122804908/226364829-2f8bddb3-854c-4e2f-a278-1f8343fd21f4.png)



1) What is a web application firewall? How do you use Nmap to detect a WAF? Perform WAF fingerprint detection using NMAP.

 A web application firewall is designed to protect web apps by filtering, monitoring, and blocking any malicious incoming HTTP traffic while also preventing  unauthorized data from leaving the application.

![image](https://user-images.githubusercontent.com/122804908/226391618-b2170985-ca53-49f9-8b0f-eefd54f30232.png)

![image](https://user-images.githubusercontent.com/122804908/226391768-63fb549f-617c-4622-877b-d8c61bde59f2.png)



2) What is EXIF data? Try to find EXIF data of images on a website using NMAP NSE.

 EXIF stands for Exchangeable Image File Format. This data is in every image file a camera records.it contains metadata of the photo.

![image](https://user-images.githubusercontent.com/122804908/226394013-ddad12e9-21d9-487e-ad71-f1cc37f43931.png)

![image](https://user-images.githubusercontent.com/122804908/226395078-7b79a75e-885c-4f8f-8c99-5ef8516dcf8b.png)


3) Use NMAP NSE to find all subdomains of the website

![image](https://user-images.githubusercontent.com/122804908/226353334-058d9676-f768-448e-b61c-5e4d3dde383a.png)

4)Perform a vulnerability scan on the target host using NMAP NSE.

![image](https://user-images.githubusercontent.com/122804908/226400334-c214e61e-6276-4781-84ba-e62ce0eedf02.png)












