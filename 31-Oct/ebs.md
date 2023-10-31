## EBS - Elastic Block Store

- EBS volumes are highly available and reliable storage volumes(Hard Drives) that can be attached to any running instance that is in the same Availability Zone.
- EBS volumes that are attached to an EC2 instance are exposed as storage volumes that persist independently from the life of the instance.
- Amazon EBS is recommended when data must be quickly accessible and requires long-term persistence. 
- EBS volumes are particularly well-suited for use as the primary storage for file systems & databases.
- Every EC2 instance must have a Root volume.
- By default, EBS "root" volumes are set to be deleted when the instance is terminated. However, you can choose to have EBS volumes persist after termination.
- You can add additional EBS volumes to instance if needed.
- Any additional volume can be attached or detached from instance at any time and is not deleted by default when instance is terminated.
- An EBS volume can attach to a single EC2 Instance only at a time.
- EBS volumes have the benefit of being backed up into a snapshot - which can later be restored into a new EBS volume.

## Lab Commands

- df -h
- sudo mkfs -t ext4 /dev/xvdf			
- sudo mkdir /add-vol
- sudo mount /dev/xvdf /add-vol
