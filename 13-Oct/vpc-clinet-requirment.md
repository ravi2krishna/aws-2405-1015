## VPC Requirement

##### Requirement Given by TCS

	- TCS is going to setup the environment i.e servers on AWS, their clients are from XYZ (REGION) Location

	- They are gonna host Servers

	- These servers are grouped into two subnets each with 4k servers

	- First Subnet is for web servers, around 4k

	- Second Subnet is for database servers, around 4k

	- In the future, they might add more number of subnets i.e application servers subnets, load balancer subnet etc

	- The web servers needs to be communicated from internet


	- The database servers needs to be communicated only from Web Servers, but not from internet

	- Coming to security of Web Servers, they should have only 
		> SSH traffic enabled for administration from internet
		> HTTP traffic for clients from internet

	- Coming to security of Database Servers, they should have only SSH access from web servers
		> SSH traffic enabled from web servers only
