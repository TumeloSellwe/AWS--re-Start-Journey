# AWS Storage Notes

**AWS Storage Services** allow you to store, manage, and secure data in the cloud with high availability and durability.  

**Benefits:**
- **Durability:** Data stored reliably across multiple Availability Zones.
- **Scalability:** Automatically scale storage up or down as needed.
- **Cost Optimization:** Pay-as-you-go pricing for different storage tiers.
- **Security:** Encryption at rest and in transit, IAM access control.

**Storage Models:**
- **Object Storage:** Amazon S3 – ideal for unstructured data.
- **Block Storage:** Amazon EBS – used with EC2 instances.
- **File Storage:** Amazon EFS – managed NFS file system for shared access.

---

## 2. AWS Storage Services

### 2.1 Amazon S3 (Simple Storage Service)
- **Purpose:** Scalable object storage for any type of data.
- **Key Concepts:** Buckets, Objects, Versioning, Lifecycle Rules, Storage Classes (Standard, IA, Glacier).
- **Use Cases:** Backup & restore, static website hosting, data lakes.

[Learn more about S3 →](https://aws.amazon.com/s3/)

---

### 2.2 Amazon EBS (Elastic Block Store)
- **Purpose:** Persistent block storage for EC2 instances.
- **Key Concepts:** Volumes, Snapshots, Provisioned IOPS.
- **Use Cases:** Databases, applications requiring low-latency storage.

[Learn more about EBS →](https://aws.amazon.com/ebs/)

---

### 2.3 Amazon EFS (Elastic File System)
- **Purpose:** Scalable file storage for Linux-based workloads.
- **Key Concepts:** NFS protocol, Shared access across multiple EC2 instances.
- **Use Cases:** Content management systems, web serving, big data analytics.

[Learn more about EFS →](https://aws.amazon.com/efs/)

---

## 3. Best Practices

- Choose the right storage type for your workload.  
- Enable versioning and lifecycle policies in S3.  
- Encrypt sensitive data using KMS.  
- Use CloudWatch to monitor storage usage.  
- Back up critical data and test restoration processes.

[Learn more about AWS Backup →](https://aws.amazon.com/backup/)

---

**This README.md provides a structured overview of AWS Storage services, key concepts, and best practices.*
