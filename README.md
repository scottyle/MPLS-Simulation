# MPLS-Simulation
This repo contains config files, images and detailed outlines of how to configure an MPLS circuit.
This simulation will be carried out in GNS3


![Alt text](Topology-MPLS.png "Topology-MPLS")

## Description of simulated scenario 

⦁	TD Bank has an On-Premises datacentre with the subnets 142.205.1.0/24, 142.205.2.0/24, 142.205.3.0/24, and 142.205.4.0/24. <br />
⦁	TD Bank has also resources in the cloud, both in Azure and AWS. <br />
⦁	TD Bank has direct connect style MPLS tunnels to Azure and AWS. <br />
    ⦁	Lumen provides the MPLS transport to Azure. <br />
    ⦁	Cogent provides the MPLS transport to AWS. <br />
⦁	Any computing resource connected to TD’s networks (142.205.1.0/24, 142.205.2.0/24, 142.205.3.0/24, and 142.205.4.0/24) must have connectivity with the compute resources in Azure and AWS. <br />
⦁	The TD compute resources located in the two cloud providers must have mutual access for replication purposes. <br />
⦁	All autonomous system networks run an underlying IGP which will be OSPF.  <br />
⦁	R1,R19 and R20 should have default routes that point towards the CE routers. The CE routers should advertise an default route using the routing protocol OSPF. <br />
    ⦁ The PE routers that connect to the cloud networks should also advertise a default route through BGP.  <br />
⦁	The Service providers networks will use VRFs (Virtual routing and forwarding) to seperate each traffic.  <br />

### GNS3 topology image 

image.png
image.png
image.png
