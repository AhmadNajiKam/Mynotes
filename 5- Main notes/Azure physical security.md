
Tags: [[Unit4]]

2024-12-19:17:42

# Architectural components 
* Physical infrastructure 
* Management infrastructure 
## Physical infrastructure 
	Physical infrastructure = datacenters 
* Datacenters are grouped into ***Regions*** and ***Availability zones*** 
* We can't access datacenters directly so you can achieve resiliency and reliability 

# [Global infrastructure](https://datacenters.microsoft.com)

## Regions 
> A region is a geographical area on the planet that contains at least one, but potentially multiple datacenters that are nearby and networked together with a low-latency network. You need to choose a region when you deploy a resource most of the time.

**Global services** : Microsoft Entra ID, Azure Traffic Manager, and Azure DNS.
**Special Regions Services** : specific VM sizes or storage types.

## Availability Zones

>Availability zones are physically separate datacenters within an Azure region. Each availability zone is made up of one or more datacenters equipped with independent power, cooling, and networking. An availability zone is set up to be an isolation boundary. If one zone goes down, the other continues working. Availability zones are connected through high-speed, private fiber-optic networks.
>![[Pasted image 20241219175407.png]]

**Important** : To ensure resiliency, a minimum of three separate availability zones are present in all availability zone-enabled regions. However, **not** all Azure Regions currently support availability zones.

# References 
