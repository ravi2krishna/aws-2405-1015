## CDN - Content Delivery Network
- A CDN (content delivery network), also called a content distribution network, is a group of geographically distributed and interconnected servers. They provide cached internet content from a network location closest to a user to speed up its delivery.

- Inside AWS, we have "Cloudfront" to achieve Content Delivery Network(CDN).

- Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds.



### Edge Locations

- An Edge location can be assumed to be a collection of physical servers within a data center to allow for content distribution to reduce latency for end users. 

- The higher the number of edge locations the better the content is distributed all over the world / region.

- An example would be CloudFront which is a CDN:
-- Cached items such as a PDF file can be cached on the edge location which reduces the amount of "space/time/latency" required for a request from the other part of the world.
