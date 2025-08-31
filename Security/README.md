# 🔐 AWS Security Notes

Security in AWS follows a **Shared Responsibility Model**:  
- **AWS:** Protects infrastructure.  
- **Customer:** Secures apps, data, and configurations.

**Key Goals:**
- Identity & Access Management
- Data Protection
- Monitoring & Auditing
- Compliance

---

## 2. AWS Security Services

### 2.1 IAM (Identity & Access Management)
- **Purpose:** Control access to AWS resources.
- **Key Concepts:** Users, Groups, Roles, Policies.
- **Best Practices:** Least privilege, MFA, role-based access.

[Learn more about IAM →](https://aws.amazon.com/iam/)

---

### 2.2 Security Groups & NACLs
- **Security Groups:** Virtual firewall for EC2 instances (stateful).  
- **Network ACLs:** Control traffic at the subnet level (stateless).

[Learn more about Security Groups →](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Security.html)  

---

### 2.3 KMS & Encryption
- **AWS KMS:** Manage encryption keys for your data.  
- **Best Practices:** Encrypt data at rest and in transit.

[Learn more about KMS →](https://aws.amazon.com/kms/)

---

### 2.4 Monitoring & Auditing
- **CloudTrail:** Tracks API calls and changes.  
- **CloudWatch:** Monitors logs, metrics, and alarms.  

[Learn more about CloudTrail →](https://aws.amazon.com/cloudtrail/)  
[Learn more about CloudWatch →](https://aws.amazon.com/cloudwatch/)

---

## 3. Best Practices

- Apply least privilege access.  
- Enable MFA for all privileged users.  
- Encrypt sensitive data using KMS.  
- Enable logging and monitoring for all resources.  

---

**This README.md provides a structured overview of AWS Security services and best practices.**
