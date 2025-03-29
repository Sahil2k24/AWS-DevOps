## 🚀 My Experience with VPCs 

Virtual Private Cloud (VPC) is a critical component in AWS that allows you to launch AWS resources into a virtual network you've defined. It offers complete control over your network configuration, including IP address ranges, subnets, route tables, and network gateways.

### 🌟 North California Region Setup

In the North California region, I created a VPC with four subnets:

- **2 Public Subnets**
- **2 Private Subnets**

Using one public route table and one private route table, I strategically configured the network for optimal performance and security. Key configurations included:

- **Bastion Host**: Deployed in the public subnet to securely access instances in the private subnet, ensuring robust security.
- **NAT Gateway**: Facilitated outbound internet traffic from the private subnets.
- **Internet Gateway**: Configured for inbound and outbound internet traffic in the public subnets.

This setup allowed me to create a load balancer and host a website in the private subnet, leveraging the security and isolation benefits.

### 🌟 Oregon Region Expansion

To expand the network, I created another VPC in the Oregon region and established VPC peering between the two VPCs. This configuration enabled seamless communication between resources in different regions, ensuring a scalable and resilient architecture.

---

### Key Takeaways

This project not only enhanced my understanding of AWS networking but also demonstrated the powerful capabilities of VPC in creating secure, scalable, and efficient cloud infrastructures. I am excited to continue exploring and implementing more advanced AWS networking solutions!

---

Check out my GitHub Profile: [Sahil2k24](https://github.com/Sahil2k24)

---

### Tags
#AWS #CloudComputing #Networking #VPC #LoadBalancer #CloudArchitecture #AWSNetworking #TechJourney #HandsOnExperience
