<h1 align="center">Total Security Solution</h1>
<h1 align="center">Built on Customizable Open Source Platform</h1>

### Building blocks for Total Security Solution are as follows,
1)	Public Cloud Infrastructure
2)	Threat Intelligence
3)	DNS Firewall
4)	Secure web gateway
5)	VPN Access Server

Public cloud infrastructure can be AWS, GCP, Azure, Linode…etc.

8 Core and 32 GB RAM is the virtual machine spec. Totally 4 virtual machines are used.

For Threat Intelligence, we use Ubuntu 18.04 LTS.

For DNS Firewall, we use CentOS 8 Stream.It sits on top of DoH (DNS over HTTPS) for deep query inspection.

For Secure Web Gateway, we use CentOS 8 Stream.It features SSL/TLS Encryption/Decryption/Authentication and LDAP Authentication/Local Authentication.

For the VPN access server (Open VPN), we use Ubuntu 20.

Programming Languages/Framework/Web Server used are Python,Shell,Django,NGINX and Kivy for client software agents.

Our Client Agent Software will look like the below,

<p align="center" ><img src="https://dimabusiness.com/git-image/DimaTS.JPG" width="600"></p> 

Overall the Architecture is built, based on Zero Trust.

Threat Intelligence API is designed in the OpenAPI way so that it can inherit 3rd party Threat Intelligence service providers, so that we can achieve accurate threat detection/analysis.

We have 4 use cases in Client Software.Live protection,Internet Access,Online Privacy and Data Privacy.

Live protection is an AntiVirus agent powered by Threat Intelligence.

Internet Access makes your internet traffic to be processed via Secure Web Gateway hosted in a public cloud supported by DNS Firewall.

Online privacy is a VPN , makes your internet traffic to be processed via VPN access server hosted in a public cloud supported by DNS Firewall.

The DNS firewall is powered by Threat Intelligence.

Data privacy features will help store your critical data encrypted and remain encrypted in transit.
The encryption and decryption private key will be handled by API on demand and it will not be stored in the client machine.In the near future we will make auto data sync to storage in the cloud as a backup solution.We will ensure the data will be encrypted in both states i.e static and transit.

Client Agent WorkFlow diagram is shown below,
<p align="center" ><img src="https://dimabusiness.com/git-image/Diagram.jpg" width="800"></p> 

