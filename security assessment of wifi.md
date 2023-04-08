
                                                      security assessment of wifi
  
                                                                                                                             Roll no:CB.EN.P2CYS22001
                                                                                                                             NAME:KARTHIKA P

1.Learn the basic working of Wi-Fi and its types with various types of attacks on it. 

Wi-Fi, short for wireless fidelity, is a technology that allows devices to connect to the internet or other networks without the need for wires or cables.
It uses radio waves to transmit data between devices and a wireless access point, which is connected to the internet or a network. 
The access point acts as a central hub that allows devices to connect to the network and communicate with each other.When a device wants to connect to a Wi-Fi network, 
it sends a request to the access point.The access point then assigns the device an IP address and allows it to communicate with other devices on the network.
The data that is transmitted between devices and the access point is encrypted using various security protocols, such as WEP, WPA, and WPA2. Encryption helps to protect the data from being intercepted
and read by unauthorized parties.

types of wifi networks:

wireless personal area network(WPAN) : They are short-range networks that connect devices within a relatively small area. A WPAN generally connects devices within a person's reach,
though the range can extend up to about 30 feet.

wireless local area network(WLAN) : They are wireless networks that use radio waves, not Bluetooth technology like WPANs. There is usually at least one cable that is the access point for internet access, such as a wired internet connection going into a router, 
which then broadcasts the wireless signal to other devices. WLANs are used for connecting to local resources and to the internet. 

wireless wide area network (WWAN) : They can be maintained over large areas, such as cities or countries, via multiple satellite systems, antenna sites or mobile phone signals. With a wide coverage area, WWANs provide a way to stay 
connected when other forms of network access are unavailable.

types of wifi aattack:

Rogue access points:A rouge access point is basically an access point that has been added to one's network without one's knowledge.This attack involves setting up a fake Wi-Fi network to trick users into connecting to it and stealing their data.

Jamming/Interference:Wireless interference basically means disruption of one's network. This is a very big challenge especially owing to the fact that wireless signals will always get disrupted.

Eavesdropping:This attack involves intercepting Wi-Fi traffic to steal sensitive information such as passwords, credit card numbers, or other personal data.

Packet sniffing:n this case, an individual is in a position of capturing a packet that one are sending across a network and see the kind of information that one are sending to a particular individual.

Man-in-the-middle (MITM) attack: This attack involves intercepting and modifying Wi-Fi traffic to gain access to sensitive information.

Password cracking: This attack involves using software to guess or crack the Wi-Fi network's password and gain access to the network.

2.Perform Wi-Fi fingerprinting using Wigile, Inssider, and Kismet.

kismet:
Kismet is a wireless network and device detector, sniffer, wardriving tool, and WIDS (wireless intrusion detection) framework.

![image](https://user-images.githubusercontent.com/122804908/230723673-61ee87ec-8abb-4933-ab34-d76f65cc1608.png)

![image](https://user-images.githubusercontent.com/122804908/230723684-875b120a-d623-435b-9aec-6a57c9e4b379.png)

we have to enable the wifi interface into monitor mode,so  can see that the mode is changed as Monitor mode. Now we are able to capture all the Wi-Fi packets that are within our range 
even if the packets are not directed to our computer or even without knowing the password of the target network.

![image](https://user-images.githubusercontent.com/122804908/230723869-de67b0dd-eeac-4f0b-b66b-81ed3fbafbb2.png)

Then we have started kismet tool in terminal,

![image](https://user-images.githubusercontent.com/122804908/230724024-1f76a5ef-6e6d-4d81-8f99-73fd8986b3db.png)

The home screen of the Kismet app looks as follows:

![image](https://user-images.githubusercontent.com/122804908/230724132-491893dd-33ff-4785-a7f4-289c7cf98e25.png)

By default ‘All devices’ are displayed and the information is updated in real-time. The ‘All devices’ tab is a dropdown menu that allows filtering of the table contents and each column is sortable 
in ascending or descending order.The SSID tab shows a list of detected routers or access points with each column being sortable and the list being searchable too

![image](https://user-images.githubusercontent.com/122804908/230724338-29a2d2cd-60e2-45ca-8093-25cb650c2ce9.png)

This section is effectively a log of what the Kismet server is detecting. It shows the date and time of each detection together with information about the router, access point or other type of wireless device. 
This information includes the physical type, MAC Address, and SSID of the device itself.

![image](https://user-images.githubusercontent.com/122804908/230724385-f4b0db9c-b936-49f5-b9cc-e33257cb77ec.png)

wigle:

WiGLE (or Wireless Geographic Logging Engine) is a website for collecting information about the different wireless hotspots around the world. Users can register on the website and upload hotspot data like GPS coordinates,
SSID, MAC address and the encryption type used on the hotspots discovered.Here we have made the wifi adapter in the monitor mode and we have used airdump to scan the networks and then the output file is saved .The csv file can be uploaded in the wigle.net and then we can obtain the present location .

![image](https://user-images.githubusercontent.com/122804908/230724589-5f8c2e80-c909-4864-a0d6-827f897dab6f.png)

![image](https://user-images.githubusercontent.com/122804908/230724678-ae98b800-adbd-42f0-9f47-528fb7dc90dd.png)

![image](https://user-images.githubusercontent.com/122804908/230724730-59538a2d-1595-47a9-973b-a14c59481060.png)

Insider:

Inssider is a Wi-Fi network scanning tool that allows users to analyze the wireless landscape around them. It can be used to detect and identify nearby Wi-Fi networks, analyze their signal strength, channel usage, and security status.

![insidder](https://user-images.githubusercontent.com/122804908/230734461-8355cfc5-e81a-4685-b58d-7873adcaaee5.jpg)


3)CreateanAccess pointwith any Wi-Fi encryption standard and start testingthe security of that connectionusing any Wi-Fi security testing tools,which should include (Aircrack-Ng, Wifite, not limited).Try to capture the 4-wayhandshake using these methods.

we have to enable the wifi interface into monitor mode,so  can see that the mode is changed as Monitor mode. Now we are able to capture all the Wi-Fi packets that are within our range 
even if the packets are not directed to our computer or even without knowing the password of the target network.

![image](https://user-images.githubusercontent.com/122804908/230724891-bda19099-8d7d-457c-9157-1eb2179dc6be.png)

Airodump-ng is used for packet capture, capturing raw 802.11 frames. 

![image](https://user-images.githubusercontent.com/122804908/230725133-fbec0637-ebf6-49d5-a5ee-9b47bbca3b2b.png)

![image](https://user-images.githubusercontent.com/122804908/230725323-360232f5-4157-490b-9fcd-8cd24cb27fee.png)

This command grabs all the traffic of wireless adapter can see and displays critical information about it, including the BSSID (the MAC address of the AP), power, number of beacon frames, number of data frames, channel, speed, encryption ,SSID.

![image](https://user-images.githubusercontent.com/122804908/230725442-e2b85ce7-cc2e-47c3-91bb-ebf822b88cb0.png)

we're now focusing on capturing data from one AP with a ESSID of 46:49:F9:20:FC:06  on channel 6 and capture critical data from it.

![image](https://user-images.githubusercontent.com/122804908/230725727-951e8d20-5c44-4d00-802b-45caead8691c.png)

In order to capture the encrypted password, we need to have the client authenticate against the AP. If they're already authenticated, we can de-authenticate them  and their system will automatically re-authenticate, where we can grab their encrypted password in the process.

![image](https://user-images.githubusercontent.com/122804908/230726160-a5aa9171-c15c-4917-8dc1-d5ec2244a510.png)

![image](https://user-images.githubusercontent.com/122804908/230726187-bfa71608-d1fb-4111-8716-39222abcfa71.png)

airodump-ng will attempt to grab their password in the new 4-way handshake.

4.After capturing the required filesfortesting, usedictionarygeneration and password cracking tools to crack the Wi-Fi password. 

a.You mustuse an existing word file to crack the password.
b.Also you have to create your dictionaryfilefor cracking the passwords.
c.Keep 3 different types of passwordsforyour Wi-Fi to test it. Simple, medium,and complex passwords can be used for testing. Simple can be a dictionary word, medium can be of dictionaryword with some numbers, and complex can be generated from any password generator online. 

we have captured the handshake by following the procedure above of the following , we have used the fasttrack.txt file to crack the password 
![image](https://user-images.githubusercontent.com/122804908/230729853-df049dc2-1bce-4bcb-9ded-12f9f82011d5.png)

Here we have created cracking20-02.txt file ,to crack the password. 
![image](https://user-images.githubusercontent.com/122804908/230729862-e9057f82-1d12-4d87-86ec-79c689aec93e.png)

![Wifi file](https://user-images.githubusercontent.com/122804908/230730888-550d9cbc-44c5-4914-8101-257fcf29aadc.jpg)

![image](https://user-images.githubusercontent.com/122804908/230729881-42ceb39a-8725-4bcc-9c9b-bfeef5b76b56.png)


6.Learn the protocol level working of WPA3 and how it differsfrom WPA2.

WPA3 (Wi-Fi Protected Access 3) is the latest security protocol for Wi-Fi networks, designed to improve upon the previous security standard, WPA2.The WPA3 protocol is designed to address the vulnerabilities and shortcomings of WPA2, which had become increasingly susceptible to attacks due to the hacking techniques.WPA3 security is designed to help prevent ,Rather than relying on shared passwords, WPA3 signs up new devices through processes that don’t require the use of a shared password.WPA3 encryption is geared to be better than previous iterations of WiFi technology.This new system, called Wi-Fi Device Provisioning Protocol (DPP), works by transmitting how to gain access to the system without transmitting a password into the air. With DPP, users use QR codes or NFC tags to let devices onto the network.28-bit encryption in WPA3-Personal mode (192-bit in WPA3-Enterprise) and forward secrecy. WPA3 also replaces the Pre-Shared Key (PSK) exchange with Simultaneous Authentication of Equals, a more secure way to do initial key exchange. The old WPA2 security has been proven vulnerable to hardware-level attacks and password vulnerabilities (using an easy password is still a dumb move). To help prevent new vulnerabilities from affecting WPA, the updated standard uses a new type of handshake that adds extra protection against password-crackers and similar brute force types of hacking.

