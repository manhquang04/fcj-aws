---
title: "Worklog Tuần 3"
date: "2024-01-01"
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Hiểu cách hoạt động của CloudFront, DynamoDB và ElastiCache.
* Tối ưu hiệu suất website bằng CDN.
* Làm quen với cơ sở dữ liệu NoSQL và bộ nhớ đệm Redis.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| :-: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | :--------: |
| 2   | - Giới thiệu khái niệm CDN và lợi ích của CloudFront <br> - Tạo CloudFront Distribution để phân phối nội dung S3 website                                                                     | 22/09/2025   | 22/09/2025      | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 3   | - Cấu hình CloudFront behavior và cache policy <br> - Test truy cập website qua CloudFront URL <br> - Thực hiện invalidation để cập nhật nội dung mới                                        | 23/09/2025   | 23/09/2025      | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 4   | - Giới thiệu DynamoDB (NoSQL Database) <br> - Tạo bảng DynamoDB (Users, Products, v.v.) <br> - Thực hành thao tác CRUD trên Console                                                          | 24/09/2025   | 24/09/2025      | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 5   | - Kết nối và truy vấn DynamoDB bằng AWS CLI <br> - Viết script nhỏ để thêm và đọc dữ liệu từ bảng                                                                                          | 25/09/2025   | 25/09/2025      | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |
| 6   | - Tìm hiểu ElastiCache (Redis & Memcached) <br> - Tạo cluster Redis cơ bản <br> - Kết nối thử từ EC2 để lưu và đọc dữ liệu cache                                                           | 26/09/2025   | 26/09/2025      | [AWS Journey](https://cloudjourney.awsstudygroup.com/) |

### Kết quả đạt được tuần 3:

* Hiểu vai trò và cách hoạt động của CDN (CloudFront) trong việc tăng tốc website.

* Tạo và cấu hình CloudFront Distribution cho web S3 hoạt động ổn định.

* Tạo được DynamoDB table, thực hiện thao tác CRUD qua Console và CLI.

* Biết tạo và test Redis cache cluster trên ElastiCache.

* Hoàn thiện mô hình web tĩnh có cache + database NoSQL để tăng tốc độ truy cập.




