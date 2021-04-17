# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Operate  
### __Stage description:__  
The Operate phase comes into play when the code has been deployed. This phase encompasses the server (or serveless) infrastructure and setting this up/monitoring it to ensure that the delopyed application runs smoothly.
With the rise of IAAS (Infrastructure As A Service) and PAAS (Platform As A Service), serviers and software can be provisioned through API's such as Azure/AWS and Google Cloud to name a few, Not only this but they can be 
further customized through these API's, either scaling up (Increasing the performance of the current server instance) or scaling out (adding additional instances to the total system). 
This allows the DevOps pipleine manage the servers themselves and respond to events such as a spike in traffic to the website or replacing a faulty instance as and when is needed, without developer intevention.



| Pipeline Stage:<br>Operate  				| Client  | System Admin  | Developer  | Product Owner  | Monitoring Team |
|-------------------------------------------|-------- |-------- |-------- |-------- |-------- |
| Provisioning IT Infrastructure (Physical or Virtual)       				|         | RAS         | C        |  IV       |         |
| Configure Scaling Out/in of Hosting (More/Less Instances)	   				|   I      |    RAS     |         |   C      |         |
| Configure Scaling up/down of Hosting (More/Less resources to current Instances) 	|   I      | RAS        |         |  C       |         |
| Configuration for gathering Statistics 	|         |    RAS     |         |         |      CV   |
| Configure Load Balancing between instances 	|         |   RAS      |    C     |         |        | 
| Monitor Compliance with Applicable Laws 	|     I    |    RAS     |         |     I    |         CV|
| Automation of Infrastructure (IaaS/PaaS) 	|         |    RAS     |         |   I      |         I|
  
  
[Home](../index.md)  
