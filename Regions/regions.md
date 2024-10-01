# AWS Services are either Regional or Global

In  **AWS** some servics are regional and if u don't see them this means you are not in the right region

**Some services are Global such as AWS IAM &S3**

---

 # AWS Regions

***Regions are cluster of DATA CENTERS**
***It consists of Availability Zones(AZs)**

## How to choose right AWS regions fo r your applications/websites?

**Data stays in your region:** Compliance with data governance and local requirements

**Closer to customers:** Keeping data close to your customers reduces lag. For instance, if your users are in Asia, storing data in an Asian region makes things faster for them.

**Service availability:** Not all services or features are available everywhere. For example, a new tool might launch in the U.S. first and come to other regions later.

**Cost differences:** Prices can vary by region, and you can check the service pricing page to see how much it will cost in your chosen region.

# Availability Zones

**Each region has multiple availability zones**

(usually 3, with a minimum of 2 and a maximum of 6). For example: us-west-1a, us-west-1b, us-west-1c

## What is an AZ? 

An AZ is a separate data center with its own power and network.

**Disaster Protection:**
AZs are isolated to avoid all being affected by a disaster.

**Fast Connection:**
AZs are linked with high-speed, low-latency networks.

*We saelect AZ when deploying our instances or DB's by choosing a subnet so we select a subnet and one subnet equals to one AZ

# Edge Locations

Edge Locations are generally used for cashing to store your data that is accessed frequently so that the customer don't have to fetch it right from the origin and we use this along with S3 or CDN(CloudFront Serivce) in AWS.

## Edge Locations are used by AWS to deliver content to users faster

**Purpose:** They help cache copies of your content closer to users, reducing latency and improving speed, especially for content delivery and streaming.

**Why Use Them:** Edge locations are part of AWS's global Content Delivery Network (CDN) called Amazon CloudFront. Using them means faster load times for your website or application, better user experience, and lower latency.

**Use Cases:** They're ideal for serving static content, live streaming, or distributing heavy files like software or updates to a global audience.

