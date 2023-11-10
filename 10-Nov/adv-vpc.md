## Bastion Host / Server

- So when we are talking about increased security, what we want to focus on is, placing of EC2 instances that are holding our data in private subnets.
- However this causes some issues, we cannot serve traffic from private instances as there is no route to the open internet and also we cannot access or ssh into EC2 instances that are in private subnets or install/update the software on those EC2 instances.
- Setting up a Bastion Host will allow you to SSH and access the EC2 private instances
- 

