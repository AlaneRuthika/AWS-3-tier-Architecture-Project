# AWS-3-tier-Architecture-Project
Designed and implemented a highly available, scalable 3-tier architecture on AWS across two Availability Zones using VPC, public and private subnets, EC2, Application Load Balancer, Auto Scaling Groups, NAT Gateway, Internet Gateway, RDS, and Security Groups. Focused on scalability, security, and reliability.

AWS 3-Tier Architecture – High Availability & Auto Scaling

📌 Project Overview

This project demonstrates the design and implementation of a highly available, scalable, and secure 3-tier architecture using Amazon Web Services (AWS). The infrastructure is designed across two Availability Zones to improve application availability, fault tolerance, and reliability.

🏗️ Architecture Diagram

"AWS 3-Tier Architecture" (project.png)

🛠️ AWS Services Used

- Amazon VPC: Created an isolated network environment.
- Public Subnets: Hosted internet-facing resources.
- Private Subnets: Hosted application and database resources.
- Amazon EC2: Provided compute capacity for web and application tiers.
- Application Load Balancer (ALB): Distributed incoming traffic.
- Auto Scaling Groups (ASG): Automatically adjusted EC2 instances based on demand.
- Internet Gateway: Enabled internet connectivity.
- NAT Gateway: Provided outbound internet access to private resources.
- Amazon RDS: Managed relational database service.
- Security Groups: Controlled traffic between architecture layers.

🏛️ Architecture Components

1. Web Tier

Handles incoming user requests through the Application Load Balancer and distributes traffic to web servers.

2. Application Tier

Processes application requests using EC2 instances deployed in private subnets.

3. Database Tier

Stores application data using Amazon RDS in private subnets.

🔄 Request Flow

1. Users send requests over the internet.
2. The Internet Gateway provides internet connectivity.
3. The Application Load Balancer distributes incoming requests.
4. Web and application tiers process requests.
5. The application tier communicates with the database tier.
6. Amazon RDS stores and retrieves application data.

🎯 Key Learnings

- AWS VPC and subnet configuration.
- Public and private network architecture.
- Load balancing and Auto Scaling.
- High availability across multiple Availability Zones.
- Network security using Security Groups.
- AWS infrastructure design and deployment.

💻 Technologies

"AWS" "EC2" "VPC" "ALB" "Auto Scaling" "RDS" "NAT Gateway" "Internet Gateway" "Security Groups"

👩‍💻 Author

Alane Ruthika

Aspiring DevOps Engineer | AWS | Linux | Cloud Computing

⭐ Conclusion

This project helped me strengthen my practical understanding of AWS cloud infrastructure, networking, high availability, scalability, and security.
