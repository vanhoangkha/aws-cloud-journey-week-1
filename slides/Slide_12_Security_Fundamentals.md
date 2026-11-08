# AWS Security Fundamentals

## Shared Responsibility Model

### AWS Responsibility (Security OF the Cloud)
- **Physical security** của data centers
- **Hardware và software infrastructure**
- **Network controls** và host OS patching
- **Hypervisor** và managed services

### Customer Responsibility (Security IN the Cloud)
- **Guest OS updates** và security patches
- **Application software** và utilities
- **AWS security groups** configuration
- **Identity và access management**

## AWS Identity and Access Management (IAM)

### Core Components
- **Users**: Individual people hoặc applications
- **Groups**: Collection của users với shared permissions
- **Roles**: Set permissions có thể assume bởi users/services
- **Policies**: JSON documents định nghĩa permissions

### IAM Best Practices
- **Principle of Least Privilege**: Chỉ cấp minimum permissions
- **Use Groups**: Assign permissions to groups, add users to groups
- **Enable MFA**: Multi-Factor Authentication cho sensitive operations
- **Rotate credentials**: Thay đổi passwords và access keys thường xuyên

## Root Account Protection
- **Không sử dụng root account** cho daily activities
- **Enable MFA** cho root account
- **Create IAM admin user** cho administrative tasks
- **Monitor root usage**: Set up CloudTrail alerts

## AWS CloudTrail
- **Log tất cả API calls** trong AWS account
- **Security analysis** và compliance auditing
- **Track changes** to AWS resources
- **Enable cho tất cả regions**

---

© Amazon Web Services, Inc. or its Affiliates.
