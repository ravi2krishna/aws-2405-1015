## Bastion Host / Server

- So when we are talking about increased security, what we want to focus on is, placing of EC2 instances that are holding our data in private subnets.
- However this causes some issues, we cannot serve traffic from private instances as there is no route to the open internet and also we cannot access or ssh into EC2 instances that are in private subnets or install/update the software on those EC2 instances.
- Setting up a Bastion Host will allow you to SSH and access the EC2 private instances

## NAT Gateway

- A NAT Gateway is designed to provide EC2 instances that live in a private subnet with a route to the internet (so they can download software packages and updates).
- A NAT Gateway will only allow incoming traffic through if a request for it originated from an instance in a private subnet.
- A NAT Gateway should be created in public subnet, but routing is done with Private Route Table.
- 

