# Cloud Security Basics

## What is Cloud Security?
Cloud security refers to the set of policies, practices, and tools used to protect cloud-based systems, data, and infrastructure from threats and unauthorized access.

Since cloud resources are accessible over the internet, security plays a very important role in cloud computing.

---

## Why Cloud Security is Important
- Cloud resources are publicly reachable if misconfigured
- Data breaches can cause financial and reputational loss
- Multiple users access cloud systems, so access control is critical
- Cloud environments change frequently, so continuous monitoring is required

---

## Shared Responsibility Model (AWS)

In cloud computing, security is a shared responsibility between the cloud provider and the customer.

### AWS is responsible for:
- Physical data centers
- Hardware and infrastructure
- Networking and physical security
- Availability of cloud services

### Customer is responsible for:
- Securing EC2 instances
- Managing IAM users and permissions
- Data encryption
- Operating system updates and patches
- Application-level security

This model ensures clear ownership of security tasks.

---

## Principle of Least Privilege
Least privilege means giving users only the permissions they need to perform their tasks and nothing more.

Benefits:
- Reduces security risks
- Limits damage in case of compromise
- Improves overall security posture

---

## Importance of Monitoring and Logging
- Monitoring helps detect performance and security issues
- Logging records system activities for auditing and troubleshooting
- Helps identify suspicious behavior early

Common examples:
- Monitoring CPU usage
- Tracking login attempts
- Reviewing access logs

---

## Conclusion
Cloud security is not a one-time setup but a continuous process.
Understanding security fundamentals like shared responsibility, least privilege, and monitoring is essential for anyone working with cloud technologies.
