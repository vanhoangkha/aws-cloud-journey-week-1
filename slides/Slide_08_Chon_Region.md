# Cách chọn Region phù hợp

## 4 yếu tố chính khi chọn Region

### 1. Compliance & Data Governance
- **Yêu cầu pháp lý**: Dữ liệu phải lưu trong nước
- **GDPR**: Dữ liệu EU phải ở trong EU
- **Quy định ngành**: Banking, Healthcare có yêu cầu riêng
- **Data sovereignty**: Chủ quyền dữ liệu

### 2. Latency (Độ trễ)
- **Gần người dùng nhất**: Giảm độ trễ mạng
- **User experience**: Tốc độ tải trang nhanh hơn
- **Real-time applications**: Gaming, trading cần độ trễ thấp
- **CDN**: Kết hợp với CloudFront để tối ưu

### 3. Service Availability
- **Không phải tất cả services** có ở mọi Region
- **New services**: Thường ra mắt ở US East (N. Virginia) trước
- **Check service availability**: Trước khi chọn Region
- **Feature parity**: Một số tính năng chỉ có ở Region nhất định

### 4. Pricing
- **Chi phí khác nhau** giữa các Regions
- **US East (N. Virginia)**: Thường rẻ nhất
- **Asia Pacific**: Thường đắt hơn US
- **Data transfer costs**: Giữa các Regions có phí

## Ví dụ cho ứng dụng tại Việt Nam
- **Tốt nhất**: Asia Pacific (Singapore) - ap-southeast-1
- **Thay thế**: Asia Pacific (Tokyo) - ap-northeast-1
- **Cân nhắc**: Asia Pacific (Sydney) - ap-southeast-2

---

© Amazon Web Services, Inc. or its Affiliates.
