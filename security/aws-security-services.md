# AWS Security Services
Amazon Web Services provides a wide range of security services to help protect data, applications, and infrastructure in the cloud. These services support identity management, threat detection, data protection, and compliance.

# Identity & Access Management
1. `IAM (Identity and Access Management)`
Manages users, groups, and roles
Controls access to AWS services using policies
Supports the least privilege principle

2. `AWS Organizations`
Manages multiple AWS accounts
Enables centralized policy control
Uses Service Control Policies (SCPs)

 # Threat Detection & Monitoring
 
1.`Amazon GuardDuty`
Threat detection service
Uses machine learning to identify suspicious activity
Detects issues like:
Unauthorized access
Compromised instances

2. `Amazon Inspector`
Automated security assessment service
Scans for vulnerabilities in EC2 instances and applications

3. `AWS Security Hub`
Central dashboard for security alerts
Aggregates findings from multiple AWS services

# Data Protection & Encryption

1. `AWS KMS (Key Management Service)`
Manages encryption keys
Integrates with many AWS services
Supports automatic key rotation

2. `AWS Secrets Manager`
Stores and manages sensitive data (passwords, API keys)
Automatically rotates secrets

3. `AWS Certificate Manager (ACM)`
Provides SSL/TLS certificates
Used to secure websites and applications

# Network & Application Protection

1. `AWS Shield`
Protects against DDoS (Distributed Denial of Service) attacks
AWS Shield has two types: Standard, which is free, and Advanced, which you have to pay for

2. `AWS WAF (Web Application Firewall)`
Protects web applications from common attacks:
SQL injection
Cross-site scripting (XSS)

# Logging & Compliance
1. `AWS CloudTrail`
Records all API calls and user activity
Useful for auditing and compliance

2. `AWS Config`
Tracks configuration changes
Helps ensure compliance with policies

# Best Practices
1. Enable MFA for all users
2. Apply the least privilege principle access
3. Encrypt sensitive data
4. Monitor logs using CloudTrail
5. Regularly review security configurations
