---
title: "Worklog Tuần 2"
date: "2024-01-01"
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Làm quen với các dịch vụ S3, RDS, Route53.
* Xây dựng website tĩnh trên S3, kết nối RDS với EC2.
* Sử dụng Route53 để trỏ domain cho website.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :-: | --- | ------------ | --------------- | :-: |
| 2 | - Tạo S3 bucket để chứa website tĩnh<br>- Upload file HTML/CSS demo lên S3 | 15/09/2025 | 15/09/2025 | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 3 | - Kích hoạt tính năng Static Website Hosting trong S3<br>- Cấu hình bucket policy cho phép public read<br>- Truy cập thử website bằng link S3 | 16/09/2025 | 16/09/2025 | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 4 | - Tạo RDS MySQL instance (Free Tier)<br>- Cấu hình VPC security group để cho phép kết nối DB<br>- Ghi nhớ endpoint & credential | 17/09/2025 | 17/09/2025 | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 5 | - Tạo EC2 instance, cài MySQL client<br>- Kết nối từ EC2 đến RDS bằng command line<br>- Test tạo database & bảng đơn giản | 18/09/2025 | 18/09/2025 | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 6 | - Tìm hiểu Route53, tạo hosted zone<br>- Thêm bản ghi A/ CNAME để trỏ domain về S3 static site<br>- Kiểm tra truy cập website bằng domain | 19/09/2025 | 19/09/2025 | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |


### Kết quả đạt được tuần 2:

* Xây dựng thành công website tĩnh trên S3.
* Truy cập được website bằng link public và bằng domain Route53.
* Tạo được RDS MySQL instance, kết nối từ EC2 thành công.
* Biết cách cấu hình Security Group, IAM role liên quan đến RDS & S3.
* Có nền tảng để tuần 3 triển khai CloudFront, DynamoDB và ElastiCache.




