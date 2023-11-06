## S3 Lifecycle Policies

- An object lifecycle policy is a set of rules that automate the migration of an object's storage class to a different storage class (or deletion) based on specified time intervals.
- By default, lifecycle policies are disabled on a bucket.
- Great for automating the management of object storage and to be more cost efficient.

## S3 Versioning

- S3 versioning is a feature to manage and store versions of an object
- S3 versioning protects your data against accidental deletion & accidental overriding
- By default, versioning is disabled on all buckets.
- Versioning can only be set on the bucket level and applies to ALL objects in the bucket.
- Once versioning is enabled, you can only "suspend" versioning. It cannot be fully disabled.
