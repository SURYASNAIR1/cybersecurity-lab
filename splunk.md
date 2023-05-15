                                                 LOG ANALYSIS USING SIEM

 ROLL NO:CB.EN.P2CYS22001

 NAME:KARTHIKA P

1. Understand the architecture of Splunk and the installation process. Setup collector and forwarder, then ensure the logs are accumulated in Splunk. 
Familiarize yourself with the dashboard fields.

A Splunk Enterprise server installs a process on  host, splunkd.splunkd is a distributed C/C++ server that accesses, processes and indexes streaming IT 

data. It also handles search requests. splunkd processes and indexes of data by streaming it through a series of pipelines, each made up of a series of 

processors.splunkd also provides the Splunk Web user interface. It lets users search and navigate data and manage Splunk Enterprise deployment through a 

Web interface. It communicates with your Web browser through REpresentational State Transfer (REST).splunkd runs a Web server on port 8089 with SSL/HTTPS 

turned on by default.It also runs a Web server on port 8000 with SSL/HTTPS turned off by default.Splunk Enterprise processes require network connectivity.


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/e26b34e3-f971-4741-bdf8-884819dc6b21)

Here ,The universal forwarder is downloaded in kali linux and then we have forwarded log files into the splunk enterprise. 

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/7f4e68b1-7a0c-412e-b063-de7d216788d5)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/a2e71e9c-1531-49bb-a06e-0fa53df03426)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/9c9b4811-32dc-4440-a22e-c4b799028be5)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/8648b83b-51e7-45fe-9d4e-7c2057b3e3b9)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/b1c52175-e145-42dc-8c5e-fbcb7aca6c42)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/6ded79b2-1922-4576-beca-d2940f3fe15c)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/5e221136-b71d-4c4e-8bb8-200215ede20d)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/5a4180c5-8688-49f4-9dbe-a556efd1e33d)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/9446e3dc-03c3-4f53-889e-ee22eedfadfa)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/ed1a1743-fbae-48be-85b0-572b91a0fac3)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/c123d6b9-79d1-47c4-9f1f-18d05bbc4540)


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/5141e5da-4ffb-429b-8b62-05b889768cdd)

2)2. Run Splunk >> Forwarder can be in the same system or another system (user’s convenience) >>Make sure the logs are indexing in the Splunk enterprise. Run any network and port scanning commands from the host to the target machine. Run at least 5 to 8 commands. (If required, any tools can also be used).

Here we have created scan.log file into the /var/log file .The nmap commands output is saved into the scan.log file by using nmapcommands>>scan.log

the nmap commands are nmap -o ,-sV,-A,finding host in subnet is performed. the the logs are forwarded into the enterprise.the name of the log file is used 

to scan the log of nmap commands are done.


![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/12f130e3-3cb3-4d8c-a16c-2c939cef0b97)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/7c38bb48-a69a-4aa7-9d08-4c834fb989d0)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/f19ed9f6-f0f1-41a1-a5c8-5a24d6b70929)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/63de435d-044a-49a6-947a-1d8d75754648)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/bcae49e8-7e77-49f4-8f2a-789ecbb62bdf)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/960e18bb-a811-47e2-8d45-e202ea0033b9)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/27070656-91bb-46b6-86f0-b17091b1ecd1)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/30fcfe30-6036-40f7-a88b-dde6d6a8631c)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/08242b9b-a20b-4979-aaf7-a8e91bb8c580)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/545321a2-2ddc-4514-8cbd-24f23298a62c)


3) Run Splunk >> Forwarder can be in the same system or another system (user’s convenience) >>Make sure the logs are indexing in the Splunk enterprise. Perform any communication using unencrypted traffic.Use the Splunk search section to check the firewall logs to analyze which application uses unencrypted data.Analyze the log file and create an alert for any further similar activities.

Here we have entered into the vulnerable website , the logs are saved and then forwarded the log into the splunk enterprise.In the splunk ,

we have searched query based on access.log.1 and the get request in the search query field,so we obtained the searches in the kali.

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/f6ae3cd3-e6c5-4908-85ab-d84be02301e6)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/62ee46db-ab80-42fe-96c2-ec35c9a2d763)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/b9176146-f2a8-434b-9167-d0b2fc2cf812)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/40cb9f4e-ae0c-460a-b692-68eff6c8b9a5)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/d429964a-d879-4a02-9d86-42d3bf971c58)

5)5. Run Splunk >> Forwarder can be in the same system or another system (user’s convenience) >>Make sure the logs are indexing in the Splunk enterprise.Logout of the target system and perform multiple failed attempts. Then use the search section to filter out the failed attempt logs. Hint: Use the “stats” command.Analyze the log file and create an alert for any further similar activities.

Here we have tried to login into the kali ,then by analysing the log in the splunk forwarder ,we can analyse by entering authentication in the query of splunk.

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/098d01ce-f4a7-48a2-92aa-5e5d123e8683)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/e5aa5bf6-5060-4296-9cd5-624a26e74a95)



