### AWS Global Infrastructure Map

The AWS Cloud spans 102 Availability Zones within 32 geographic regions around the world, with announced plans for 12 more Availability Zones and 4 more AWS Regions in Canada, Malaysia, New Zealand, and Thailand. 

- Amazon Cloud Computing resources(servers, storage, databases etc) are available across the world. 
In easy words if we see this then Amazon Data Centers are available in different geographical locations.

- Organizations can register their presence and launch their product using these Data Center in any Location
- https://aws.amazon.com/about-aws/global-infrastructure/

#### AWS High Level View Of Infrastructure
In terms of AWS, it’s infrastructure is made up of 
 - Regions
 - Availability Zones
 - Edge Cache/Locations

#### Regions
- Amazon Data Centers are available in different Geographical Locations, which are termed as REGIONS.
- Regions are designed to service AWS customers (or your users) that are located closest to a region.
- Price varies from region to region
- AWS Price Calculator https://calculator.aws/#/
- Availability of Services are different for different AWS Regions.
- Few Services are available in ALL(GLOBAL) AWS Regions.

#### Availability Zones
- The Availability zones are where the actual data centers are located.
- So within a Region there can be multiple Availability zones which are physically separated but are connected through low latency and high speed internet connections.
- AZ’s are physically separated by a meaningful distance, many kilometers, from any other AZ, although all are within 100+ km (60+ miles) of each other.
- https://docs.aws.amazon.com/images/AWSEC2/latest/UserGuide/images/region-with-azs.png
- "Properly designed applications will utilize multiple availability zones for High Availability and  Fault Tolerance"
- Single Zone Setup : https://s3.amazonaws.com/awsmp-fulfillment-cf-templates-prod/08be5b5c-87e6-4dde-834b-56ac8c2fb521.59a1e99b-b86c-49ef-acf9-c460450db888.png
- Multi Zone(HA) Setup : https://d2908q01vomqb2.cloudfront.net/fc074d501302eb2b93e2554793fcaf50b3bf7291/2018/03/23/wordpress-on-aws.png
