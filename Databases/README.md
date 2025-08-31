# 🗄AWS Database Notes

AWS provides managed database services that allow you to store, query, and scale data without managing infrastructure.  

**Benefits:**
- Fully managed, highly available, and scalable.
- Automated backups and patching.
- Secure access using IAM and encryption.

**Database Models:**
- **Relational:** Amazon RDS, Aurora.
- **NoSQL:** DynamoDB.
- **In-memory:** Amazon ElastiCache.

---

## 2. AWS Database Services

### 2.1 Amazon RDS (Relational Database Service)
- **Purpose:** Managed relational databases (MySQL, PostgreSQL, SQL Server, etc.).
- **Key Concepts:** Multi-AZ, Snapshots, Read Replicas.
- **Use Cases:** Web applications, enterprise apps, CRM/ERP systems.

[Learn more about RDS →](https://aws.amazon.com/rds/)

---

### 2.2 Amazon DynamoDB
- **Purpose:** NoSQL database for key-value and document data.
- **Key Concepts:** Tables, Items, Partition Key, Global Secondary Index.
- **Use Cases:** High-traffic web apps, mobile backends, IoT applications.

[Learn more about DynamoDB →](https://aws.amazon.com/dynamodb/)

---

### 2.3 Amazon Aurora
- **Purpose:** High-performance MySQL/PostgreSQL-compatible relational database.
- **Key Concepts:** Serverless option, replication across AZs.
- **Use Cases:** Enterprise-grade applications with high throughput.

[Learn more about Aurora →](https://aws.amazon.com/rds/aurora/)

---

## 3. Best Practices

- Enable Multi-AZ for high availability.  
- Use snapshots for backup and recovery.  
- Monitor performance with CloudWatch.  
- Encrypt sensitive data using KMS.  
- Choose the correct database type for your workload (relational vs. NoSQL).

---

**This README.md provides a structured overview of AWS Database services and best practices.**
