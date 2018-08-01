# devops-training

- Create VPC
- Create Internet Gateway and associate to VPC
- Create Subnets (in different Availablbilily Zones) and associate to VPC
- Create Route Table and associate to both Subnets
- Create ACL and associate to both Subnets
- Create a Load Balancer Security Group (allow 80 incoming, 80,443 outgoing)
- Create a Instances Security Group (allow above LBSG and 22 incoming)
- On EC2, create a Load Balancer, add both Subnets, assign above LBSG
