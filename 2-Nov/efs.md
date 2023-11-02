## EFS - Elastic File System

- EFS storage capacity is elastic. The storage capacity will increase and decrease as you add or remove files.
- Supports the Network File system (add NFS port) while wirking with EFS.
- NFS port 2049, should be added on EFS file system Secuirty Group.
- Best performance when using an EC2 AMI with Linux kernel 4.0 or newer
- EFS is not used as boot volume, not as ROOT volume, only additional volume.
- The EFS file system can be accessed by one (or more) EC2 instances at the same time, across different Availbility Zones.
- EFS can scale to petabytes in size.
- To access EFS file system in VPC, you can create one or more mount targets in the VPC.
- If there are multiple subnets in an AZ, you can create a mount target in one of the subnets, then all the instances in that AZ will share the mount target.
- AWS recommends that you create mount targets in all the AZ's, so that you can easily mount the file system on EC2 instances that you might launch in any zone in future, as there are no charges for mount targets.
- EFS Offers storage classes to minimise the costs.
- Standard : used to store frequently accessed data i.e daily accessed.
- Infrequent Access : It's a lower cost storage class that's designed for infrequently accessed files(not accessed everyday).
- https://cloudwellserved.com/wp-content/uploads/2018/10/EFS_VPC.png
