# What is Cloud Computing?
`Cloud Computing` is the on-demand delivery of IT resources over the internet with the pay as you go pricing.

# Evolution of Cloud Hosting
1. `Dedicated Server` - This is a single machine dedicated to a single business that runs a single web app or website.
2. `Virtual Private Server (VPS)` - One physical machine dedicated to a single business. The machine is virtualized into multiple sub-machines. Can run multiple web apps or websites.
3. `Shared Hosting` - One physical machine shared by hundreds of businesses.Relies on tenants under-utilizing resources. Very cheap but has: Limited functionality and Poor isolation.
4. `Cloud Hosting` - Multiple physical machines act as one system. Resources are abstracted into cloud services. Key features: Flexible, Scalable, Secure, Cost-effective, and highly configurable.

# AWS Cloud History
`Amazon Web Services (AWS)` is a comprehensive cloud computing platform provided by Amazon. While Amazon began offering web services as early as 2002, AWS officially launched 
its modern form in 2006. Its first publicly available service was the `Amazon Simple Queue Service (SQS)`, which was released in late 2004. The platform's foundation was 
solidified in 2006 with the launch of `Amazon Simple Storage Service (S3)` in March and `Amazon Elastic Compute Cloud (EC2)` in August. 
A major milestone was reached in November 2010 when all of Amazon’s global retail web traffic migrated to AWS infrastructure. 
To standardize industry skills and training, AWS introduced its global certification program in April 2013. 
Today, AWS remains the world's leading cloud service provider by market share, offering over 200 fully featured services from data centers globally.

# What is a Cloud Service Provider?
A `Cloud Service Provider` is a company that provides multiple cloud services.
The Cloud Service Providers can be grouped into 3 tiers:
1. Tier 1(Top tier)- They were in the market, they have a wide offering of services, and they are well recognized in the industry. They include: `AWS`, `Microsoft Azure`, `Google Cloud Platform`, and `Alibaba.`
2. Tier 2(Mid-tier)- Backed by well-known tech companies, slow to innovate, and has turned into a specialization. They include: `IBM Cloud`, `Oracle Cloud`, `Huawei Cloud`, and `Tencent Cloud.`
3. Tier 3(Light tier)- They are virtual private servers turned to offer core IAAS offerings. They are simple and cost-effective. They include: `Vultr`, `Digital Ocean`, and `Akamai Connected Cloud (Linode).`

# AWS Global Infrastructure
1. `Region`-They are physical locations around the world containing multiple data centers. A region is a cluster of data centers. Region names include: `us-east-1.`
2. `Availability Zone`- is one or more discrete data centers within a region with redundant power, networking, and connectivity. AZs are separated from each other to ensure they are isolated from disasters. They are connected with high-bandwidth, ultra-low-latency networking. AZs name include: `us-east-1a, us-east-1b`
3. `Local Zones`- Local Zones bring AWS services closer to users. Designed for ultra-low latency (milliseconds). Used for: Gaming, Real-time apps, media, and machine learning.
4. `Edge Locations`- enables the content to be delivered to end users with lower latency.
5. `AWS Outposts`- They extend AWS infrastructure to on-premises environments. Run AWS services in your own data center. Supports hybrid cloud setups. Useful for low-latency or local data requirements.
