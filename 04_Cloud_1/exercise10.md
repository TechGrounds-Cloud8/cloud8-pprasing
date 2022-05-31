# VPC
Set up a vpc with public and private subnets. Add a security group and connect to a EC2 instance in the public subnet

## Key terminology
...

## Exercise
### Sources
none

### Overcome challanges
- customize subnet cidr.
- change the name of the routetables and subnets by changing the tag

### Results
**Exerise 1:**  
Created a vpc with the wizard
![screenshot](../00_includes/vpc-wizard.jpg)

**Exerise 2:**  
Add 2 subnets without the wizard (Public Subnet 1 + Private Subnet 2)
![screenshot](../00_includes/vpc-add-subnet.jpg)

Associate 2 private subnets to the private route table
![screenshot](../00_includes/vpc-subnet-ass-private.jpg)

Associate 2 public subnets to the public route table
![screenshot](../00_includes/vpc-subnet-ass-public.jpg)

**Exerise 3:**  
Add security group
![screenshot](../00_includes/vpc-create-security-group.jpg)

**Exerise 4:**  
Create EC2 instance and connect to IPv4 link 18.195.176.231 (without SSL!!!!)
![screenshot](../00_includes/connect-2-webserver.jpg)

**Elastic IP association exercise:**  
Connect the elastic IP address to the instance
![screenshot](../00_includes/elastic-IP-adress-association.jpg)
![screenshot](../00_includes/elastic-IP-adress-association2.jpg)




