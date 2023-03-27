1. Perform Password stealing (over plaintext) using ARP Cache Poisoning attacks

Here we have used ettercap to find out the  credentials typing in the target website.In this we have fixed target host and then we have started arp poisioning in the host and then we have tried 

to login in the website from the host ,we can get the credentials they have entered.

![image](https://user-images.githubusercontent.com/122804908/227955793-3f3b25c9-9328-4db6-8bc9-f7d40fc42efa.png)

![image](https://user-images.githubusercontent.com/122804908/227955852-73888b79-f9c4-47f1-adfe-95c96d0a3aa8.png)

2. Perform Denial of Service (DoS) attacks using ARP Cache Poisoning attacks

A denial-of-service attack is a cyberattack that makes a computer or other device unavailable to its intended users. we have fixed target and then we have used arp 

poisioning dos attack plug in and then when we tried to enter the webites in the host,it cannot be accessed.

![image](https://user-images.githubusercontent.com/122804908/227956964-f583f7a1-cb94-4c7a-bacb-6a251c6eb231.png)


![image](https://user-images.githubusercontent.com/122804908/227957060-9340e232-3374-4722-a05f-f9dafd8e4b57.png)

3. Perform DNS Spoofing attack using ARP Cache Poisoning attacks

 DNS Attack is any attack targeting the availability or stability of a network's DNS service. Here we have tried to get the page which we have created instead of the original login page.
 
 ![image](https://user-images.githubusercontent.com/122804908/227957780-5156bed0-1df3-40eb-826a-95acdb22222a.png)

 here  we have created an html page for our ip address in the HTML folder

![image](https://user-images.githubusercontent.com/122804908/227958022-3b7c717b-51e0-4cca-b520-5566675f7cff.png)

we have entered the corresponding website and its spoof ip in the dns page.

![image](https://user-images.githubusercontent.com/122804908/227958576-5c7102fd-babe-4930-8dac-00185b54c70c.png)

![image](https://user-images.githubusercontent.com/122804908/227959025-b7920993-8f2d-4d87-af1b-e05bfdc79274.png)

![image dns](https://user-images.githubusercontent.com/122804908/227959810-707130f8-aa15-42bf-bc2d-9a371bfd65bc.jpg)

In this dns attack  we have swapped the ip address of the given website as our ip address so it will direct to our own malicious webpage.

4. Invoke ‘sslstrip tool’ for stealing passwords from any machine that is connected to a LAN by stripping the HTTPS connection. 

It is an action performed by a malicious user that leads to a downgrade from an HTTPS secure connection to a less secure encrypted HTTP connection. here we have edited 

the etter.conf file by making it as commands so, here the secured connection will be degraded into the unsecured connection,by making degraded version of website ,we

can take the credentials 

![image](https://user-images.githubusercontent.com/122804908/228022701-8589abb1-23e7-4993-b312-157589c3bbe5.png)

![image](https://user-images.githubusercontent.com/122804908/228023120-66b76128-4ce1-4050-a4db-e0026c751dc4.png)

![image](https://user-images.githubusercontent.com/122804908/228023176-9bf457fd-33ad-4683-aea3-49022a396099.png) 

![image](https://user-images.githubusercontent.com/122804908/228023223-d6767841-a4cc-4d6e-9df4-717a5929bae6.png)




 
