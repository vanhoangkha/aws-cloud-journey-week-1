# AWS Account & Billing

## Thiết lập tài khoản AWS

### Root Account
- **Email address** làm username duy nhất
- **Full access** to all AWS services và billing
- **Không nên sử dụng** cho daily activities
- **Bắt buộc enable MFA** cho bảo mật

### IAM Users
- **Tài khoản con** với permissions giới hạn
- **Best practice**: Tạo IAM admin user cho daily work
- **Programmatic access**: Access keys cho CLI/SDK
- **Console access**: Username/password cho web interface

## Mô hình tính phí AWS

### Pay-as-you-go
- **Không có upfront costs** hoặc long-term contracts
- **Pay only for what you use**
- **Scale up or down** based on business needs

### Pay less when you reserve
- **Reserved Instances**: 1-3 year commitments, up to 75% savings
- **Savings Plans**: Flexible pricing model
- **Spot Instances**: Up to 90% discount for flexible workloads

### Pay even less per unit by using more
- **Volume discounts** for higher usage
- **Tiered pricing**: Cost decreases as usage increases
- **Free data transfer** within same AZ

### Custom pricing
- **Enterprise customers** với large volumes
- **Contact AWS Sales** for custom deals
- **Private pricing agreements**

---

© Amazon Web Services, Inc. or its Affiliates.
