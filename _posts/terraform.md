## Terraform by Hashicorp

With the increasing adoption of cloud platforms the provisioning, maintaining and deprovisioning of cloud resources at scale became an issue. To give an example, let's 
say a company A consists of thousands of employees working on N services. Now each of these services needs dev ops folks to maintain service specific resources. Developers 
understand code and what if there was an easy way in which developers could provision their service specific resources just by typing in few lines of code without having 
to bug the dev ops team eveytime? IaaC or Infrastructure as Code tools solve this problem. 

Back in 2012, AWS released CloudFormation, an IaaC tool for provisioning AWS resources. The problem was that CloudFormation provided support only for AWS. What if
your enterprice deals with other cloud platforms or maybe deals with multiple cloud platforms at a time? This painpoint lead to the inception of Terraform. 
Terraform is an open source IaaC tool which helps us provision, maintain and destroy cloud resources with a support for a wide range of cloud platforms such as GCP, Azure, AWS,
DigitalOcean, etc. Terraform 1.0 was released in 2014 with support for AWS and DigitalOcean, but it gained traction only since 2017.
