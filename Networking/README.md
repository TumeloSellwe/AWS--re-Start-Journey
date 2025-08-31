# AWS Networking Notes

Networking in AWS allows you to securely connect resources, control traffic, and provide low-latency access.  

**Key Concepts:**
- **VPC (Virtual Private Cloud):** Isolated network for your resources.
- **Subnets:** Divide VPC into smaller segments.
- **Route Tables:** Control traffic routing.
- **Security:** Control access using Security Groups and NACLs.

---

## 2. AWS Networking Services

### 2.1 VPC & Subnets
- **Purpose:** Isolate and organize resources.
- **Key Concepts:** Public vs Private subnets, Internet Gateway (IGW), NAT Gateway.
- **Use Cases:** Secure deployment of web apps, databases, and internal services.

[Learn more about VPC →](https://aws.amazon.com/vpc/)

---

### 2.2 Route 53 & DNS
- **Purpose:** Managed DNS service.
- **Use Cases:** Route user traffic to AWS services or external endpoints.

[Learn more about Route 53 →](https://aws.amazon.com/route53/)

---

### 2.3 Load Balancers & Global Accelerator
- **Purpose:** Distribute traffic and improve availability.
- **Key Concepts:** ALB (Application), NLB (Network), Global Accelerator for global traffic.
- **Use Cases:** High availability web apps, microservices architecture.

[Learn more about ELB →](https://aws.amazon.com/elasticloadbalancing/)  
[Learn more about Global Accelerator →](https://aws.amazon.com/global-accelerator/)

---

## 3. Best Practices

- Use private subnets for sensitive resources.  
- Apply Security Groups and NACLs for layered security.  
- Use Route 53 for DNS failover.  
- Monitor network traffic with VPC Flow Logs.  

---

**This README.md provides a structured overview of AWS Networking concepts and services.**
