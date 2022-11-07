# MPLS-Simulation
This repo contains config files, images and detailed outlines of how to configure an MPLS circuit 


image.png

## Description of simulated scenario 

⦁	TD Bank has an On-Premises datacentre with the subnets 142.205.1.0/24, 142.205.2.0/24, 142.205.3.0/24, and 142.205.4.0/24. 
⦁	TD Bank has also resources in the cloud, both in Azure and AWS.
⦁	TD Bank has direct connect style MPLS tunnels to Azure and AWS.
    ⦁	Lumen provides the MPLS transport to Azure.
    ⦁	Cogent provides the MPLS transport to AWS.
⦁	Any computing resource connected to TD’s networks (142.205.1.0/24, 142.205.2.0/24, 142.205.3.0/24, and 142.205.4.0/24) must have connectivity with the compute resources in Azure and AWS. 
⦁	The TD compute resources located in the two cloud providers must have mutual access for replication purposes.


