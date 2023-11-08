## IAM Role

- An IAM role is similar to a user, in that it is an AWS identity with permission policies that determine what the identity can and cannot do in AWS.
- IAM role does not have standard long-term credentials (password or access keys)
- IAM internally use STS - Security Token Service
- STS allows you to create a temporary security credentials that grant trusted users access to your AWS resources
- Service to service permissions need IAM Role
