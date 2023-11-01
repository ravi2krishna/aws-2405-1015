## Limitations Of EBS

- You cannot get the data across multiple availability zones.
- You cannot connect multiple instances to same EBS volume

## Snapshots

- A Snapshot is an "backup" of EBS Volume.
- A Snapshot is not an active EBS Volume, so we cannot attach snapshot to EC2 Instance.
- To restore a snapshot, we need to create Volumes from the Snapshot.
- Snapshots cost less, compared to EBS Volumes, as they are inactive data.
- Internally Snapshots are stored in S3
- Snapshots helps you get data across Mutiple Zones & Mutiple Regions, increasing data durability.
- You can take Snaphots agaiant Additional Volume and Root Volumes.
- If you creata a custom AMI, you'll get an implicit automated Snapshot.
