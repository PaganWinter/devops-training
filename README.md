# devops-training

- Create VPC
- Create Internet Gateway and associate to VPC
- Create Subnets (in different Availablbilily Zones) and associate to VPC
- Create Route Table and associate to both Subnets
- Create ACL and associate to both Subnets
- Create a Load Balancer Security Group (allow 80 incoming, 80,443 outgoing)
- Create a Instances Security Group (allow above LBSG and 22 incoming)
- On EC2, create a Load Balancer, add both Subnets, assign above LBSG

- Create AMI from existing VM
- Create Launch Configuration
- Create Auto Scaling Group with above LC

Docker Commands:

docker
ps : list running containers
ps -a : list all containers
run : run a container
stop <cid|name> : stop a container
start <cid|name> : start a container
restart <cid|name> : restart a container
pause <cid|name> : pause a container
unpause <cid|name> : unpause a container
exec : issue command inside running container
inspect <cid|name> : view container details
rm <cid|name> : remove a container
images : list all images
build : build an image
tag : name an image
pull : pull image from hub to local
rmi <> : push image to hub from local
inspect <> :
