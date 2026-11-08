# Các mô hình dịch vụ Cloud

## Infrastructure as a Service (IaaS)
- **Định nghĩa**: Cung cấp hạ tầng máy tính ảo hóa
- **AWS Services**: Amazon EC2, VPC, EBS
- **Khách hàng quản lý**: OS, Runtime, Applications, Data
- **AWS quản lý**: Hardware, Hypervisor, Network

## Platform as a Service (PaaS)
- **Định nghĩa**: Cung cấp platform phát triển ứng dụng
- **AWS Services**: Elastic Beanstalk, Lambda, RDS
- **Khách hàng quản lý**: Applications, Data
- **AWS quản lý**: Runtime, OS, Infrastructure

## Software as a Service (SaaS)
- **Định nghĩa**: Cung cấp ứng dụng hoàn chỉnh
- **AWS Services**: WorkMail, Chime, QuickSight
- **Khách hàng quản lý**: User access, Data input
- **AWS quản lý**: Everything else

## Ma trận trách nhiệm
| Thành phần | IaaS | PaaS | SaaS |
|------------|------|------|------|
| Applications | Khách hàng | Khách hàng | AWS |
| Data | Khách hàng | Khách hàng | Chia sẻ |
| Runtime | Khách hàng | AWS | AWS |
| OS | Khách hàng | AWS | AWS |
| Infrastructure | AWS | AWS | AWS |

---

© Amazon Web Services, Inc. or its Affiliates.
