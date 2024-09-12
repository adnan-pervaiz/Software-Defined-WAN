![image](https://github.com/user-attachments/assets/1eacfd28-b078-4d88-842d-ab48c633bb4a)# Software-Defined-WAN
Basic of Software Defined 

![image](https://github.com/user-attachments/assets/13c3d2de-f92e-4b8a-91f4-dff3f0c24677)

SDN Comparison wiht Traditional Networks

![image](https://github.com/user-attachments/assets/25b2faa1-a5c8-4395-bf24-a18217780150)

SDWAN Over MPLS

![image](https://github.com/user-attachments/assets/c1a0b1c9-f9ea-4b37-88f1-1afa319d2722)

Separate Control Plane and Data Plane

1. Transitions the architecture from being device-centric to network-centric

2. Creates the ability to program the network

3. Enables significant improvements in control and visibility

4. Simplifies the network – even as traffic flows become more complex

5. Facilitates the creation of services within the network

6. Establishes a framework to virtualize components of the network

Enterprise WAN challenges 

![image](https://github.com/user-attachments/assets/afca1c7f-e6e4-428f-979e-530f83a19a0a)

Software Defined WAN (SD-WAN)

1- Simplified Management and Orchestration (Provisioning, Management, Configuration)

2- Utilizing diverse transport effectively (Reducing costs via broadband Internet, increasing bandwidth and utilization)

3-Increased Visibility and Security in the enterprise

![image](https://github.com/user-attachments/assets/79ad1fa9-c98d-46b3-9a9e-57f95badc200)


Universal CPE (Universal Customer Premises Equipment)

With universal CPE, the CPE hardware is based on standard x86 servers which can run multiple virtualized network functions


![image](https://github.com/user-attachments/assets/023eb245-6d80-49f1-8a5f-d1ce8538d420)


SD-WAN Solution Components

![image](https://github.com/user-attachments/assets/974a5f56-6b7f-4c54-a7fe-8f6ff3f537cd)



SD-WAN Hub and Gateway

The main use case for using SD-WAN gateways is in the case where it needs to interconnect SD-WAN  islands with non-SD-WAN islands. Two sub-use cases can be distinguished here gradual migration and  hybrid environment (SD-WAN sites to non-SD-WAN sites use cases).
As previously described, SDWAN Gateway is a FlexVNF instance that will act as a transition point between  regular MPLS VPN domain and the SDWAN domain. One should consider a SDWAN Gateway as a hybrid  branch CPE which has legs in both domains. A SDWAN Gateway serves as a Hub for data plane traffic needs to pass from one domain to the other. One of the key role of the SD-WAN Gateway is to  appropriately distribute routing information between both worlds authorizing the creation of forwarding path  between those two environments.

Another use case covered by SDWAN Gateway is hybrid deployment which is the same as gradual  migration use case (until all branches have migrated to SDWAN environment). In hybrid environment, not  all branch sites of a given enterprise customer are upgraded with Versa FlexVNF to act as SD-WAN CPEs,  though all sites must be enabled with connectivity. In hybrid deployments, non-Versa sites may be  connected via the MPLS backbone of a single provider or multiple providers using traditional PE-CE  connection model. The diagram below illustrates an example hybrid deployment where some branch sites  are connected to the Provider-1 network with Versa FlexVNF and other branch sites are connected to the  Provider-2 MPLS based network using a traditional PE-CE model.













