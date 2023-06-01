                                                     INVESTIGATING WITH  ELK 01

we will learn how to utilize the Kibana interface to search, filter, and create visualizations and dashboards, while investigating VPN logs for anomalies. 


Elastic stack:

the collection of different open source components linked together to help users take the data from any source
 
Elasticsearch:

analytics engine used to store JSON-formated documents,used to store, analyze, perform correlation on the data

Logstash:

take the data from different sources, apply the filter on it or normalize it, and then send it to the destination 

It Is divided into three parts: input ,filter ,Output

Beats:

it is used to ship/transfer data from the endpoints to elasticsearch.

Kibana:

Kibana is a web-based data visualization that works with elasticsearch to analyze, investigate and visualize the data stream in real-time.

TASK 5:

Select the index vpn_connections and filter from 31st December 2021 to 2nd Feb 2022. How many hits are returned?

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/2282c54e-bbc8-4eff-b5a2-91f05a2f01f0)

Which user is responsible for max traffic?



![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/a85ee29c-837d-4d22-bb9e-80fe80cfe704)

Which IP address has the max number of connections?

For this we have to search in source ip.

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/83d0b6fa-1f40-4231-ae6b-846ab50ed166)

Create a table with the fields IP, UserName, Source_Country and save.

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/0ded427e-bb65-4a87-ac79-46b781df23bc)

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/b58efb6f-a02f-49f1-a582-255357a459e4)

Apply Filter on UserName Emanda; which SourceIP has max hits?

Here in the search filter ,we have entered emanda and then searched in source ip 

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/5d49fa06-351f-48fe-8382-823b21b0f227)

On 11th Jan, which IP caused the spike observed in the time chart?

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/21ba073e-f840-4d3c-93b6-91ad7c086e42)

How many connections were observed from IP 238.163.231.224, excluding the New York state?

First we have to search ip address , and then in that we have to search timestamp it will have 96 documents.after filtering it with newyork ,we will get 48 documents. 

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/75fbb0bc-eb27-4a51-bd10-98c89c3646e3)

TASK 6:

Create a search query to filter out the logs from Source_Country as the United States and show logs from User James or Albert. How many records were returned?

we have to search  the query language unitedstates and james or albert

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/c0b2e373-8beb-4d4e-947f-7a2f967dd2e5)

As User Johny Brown was terminated on 1st January 2022, create a search query to determine how many times a VPN connection was observed after his termination.

1

TASK 7:

Which user was observed with the greatest number of failed attempts?

Here we have used action  and then logged into failed attempts.

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/aef80681-3e4c-40aa-9998-a99ff6d18b5c)

How many wrong VPN connection attempts were observed in January?

Here  we have filtered the month of january and then used the action:failed attempts to visualize the data. 

![image](https://github.com/karthu12/cybersecurity-lab/assets/122804908/c99d54a1-04e8-45aa-b631-cc9e06dd6abb)







