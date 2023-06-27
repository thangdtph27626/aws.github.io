<p align="center">
 <h1 align="center">Tổng quan AWS </h1>
</p>

## AWS là gì?

Amazon Web Services (AWS) là nền tảng dịch vụ đám mây an toàn, mang đến khả năng tính toán, lưu trữ cơ sở dữ liệu, phân phối nội dung và các chức năng khác nhằm giúp các doanh nghiệp mở rộng và phát triển.

Trước đây muốn có một trang web hay một ứng dụng nào đó, các công ty đều phải có hệ thống server vật lý của riêng mình. Việc mua các thiết bị phần cứng đã tốn kém rồi, việc lắp đặt và cài cắm cho chúng hoạt động càng tốn thời gian hơn. Hơn nữa, việc vận hành vào bảo trì sẽ cần có nhân viên IT chuyên trách, khó khăn trong việc mở rộng khi lượng người dùng tăng cao, hay giảm xuống trong các giờ thấp điểm - Khả năng scale rất thấp. Túm lại là chi phí rất cao. Điện toán đám mây là giải pháp cho vấn đề này.

Để bắt đầu với AWS các bạn có thể đăng ký tại đây: [aws.amazon.com](aws.amazon.com)

## Dịch vụ điện toán đám mây mà AWS cung cấp gồm những gì?

### Compute

- Amazon Elastic Computer Cloud (EC2): dịch vụ máy chủ ảo
- Elastic Load Balacing (ELB): dịch vụ cân bằng tải
- AWS Lambda: dịch vụ triển khai code không server (serverless)
- AWS Elastic Beanstalk: triển khai các ứng dụng web
- VM Import/Export: import/export ảnh các máy ảo
  
### Storage and Content Delivery

- Amazon S3: dịch vụ lưu trữ đối tượng
- Amazon Glacier: dịch vụ lưu trữ dữ liệu ít truy cập
- Amazon Elastic Block Store (EBS): dịch vụ lưu trữ dạng khối, phục vụ cho EC2 nhưng độc lập EC2.
- Amazon Elastic File System (EFS): dịch vụ lưu trữ và chia sẻ file.
- Amazon CloudFront: dịch vụ phân phối nội dung (content delivery)
- Amazon Storage Gateway: dịch vụ cổng lưu trữ dữ liệu
- Amazon AWS Import/Export Snowball: dịch vụ di chuyển dữ liệu trực tiếp lên đám mây của AWS

### Database

- Amazon RDS: dịch vụ cơ sở dữ liệu mô hình quan hệ Amazon Aurora, Oracle, Microsoft SQL Server, PostgreSQL, MySQL & MariaDB.
- Amazon DynamoDB: dịch vụ cơ sở dữ liệu NoSQL của Amazon
- Amazon Redshift: dịch vụ kho dữ liệu của Amazon
- Amazon ElastiCache: dịch vụ cache dữ liệu của Amazon


### Networking

- Amazon VPC: dịch vụ mạng riêng ảo
- Amazon Direct Connect: dịch vụ thiết lập kết nối dành riêng từ AWS đến DataCenter.
- Amazon Route53: dịch vụ quản lý tên miền DNS và định tuyến đến các dịch vụ của AWS.

### Deleloper tools

- Amazon CodeCommit: dịch vụ quản lý code, có thể giao tiếp với git.
- Amazon CodeDeploy: dịch vụ triển khai code tự động lên các máy chủ ảo EC2, Lambda
- Amazon CodePipeline: dịch vụ liên quan đến code như cập nhật, biên dịch, test, …

### Management Tools

- Amazon CloudWatch: giám sát các nguồn tài nguyên
- AWS CloudFormation: quản lý các nguồn tài nguyên
- AWS CloudTrail: dịch vụ lưu lại lịch sử hoạt động các dịch vụ
- AWS Config: dịch vụ quản lý cấu hình AWS
- AWS OpsWorks: dịch vụ định nghĩa cấu trúc ứng dụng
- AWS Service Catalog: dịch vụ quảng lý danh mục dịch vụ IT trên AWS
- AWS Trusted Advisor: công cụ trực tuyến giám sát giới hạn dịch vụ

### Security and Identity

- AWS Identity and Access Management: quản lý người dùng và quyền truy cập dịch vụ AWS
- AWS Key Management Service (KMS): quản lý khóa mã hóa các dịch vụ
- AWS Directory Service: quản lý và truy cập các tài nguyên dễ dàng
- AWS WAF: dịch vụ tường lửa cho các ứng dụng web
- AWS CloudHSM: dịch vụ bảo mật các mô đun phần cứng. Sinh và quản lý khóa mã hóa.

## Tại sao doanh nghiệp nên chọn AWS là giải pháp điện toán mây?

Với AWS bạn không phải cung cấp tài nguyên quá mức để xử lý các hoạt động kinh doanh ở mức cao nhất trong tương lai. Thay vào đó, bạn cung cấp lượng tài nguyên mà bạn thực sự cần. Bạn có thể tăng hoặc giảm quy mô của các tài nguyên này ngay lập tức để tăng và giảm dung lượng khi nhu cầu kinh doanh của bạn thay đổi.

### Tiết kiệm chi phí
Nền tảng đám mây cho phép bạn thay chi phí vốn (trung tâm dữ liệu, máy chủ vật lý, v.v.) bằng chi phí biến đổi và chỉ phải chi trả cho những tài nguyên CNTT mà bạn sử dụng. Bên cạnh đó, chi phí biến đổi cũng sẽ thấp hơn nhiều so với chi phí bạn tự trang trải do tính kinh tế theo quy mô.

### Triển khai trên toàn cầu chỉ trong vài phút
Với đám mây, bạn có thể mở rộng sang các khu vực địa lý mới và triển khai trên toàn cầu trong vài phút. Ví dụ: AWS có cơ sở hạ tầng trên toàn thế giới, vì vậy, bạn có thể triển khai ứng dụng của mình ở nhiều địa điểm thực tế chỉ bằng vài cú nhấp chuột. Đặt các ứng dụng gần hơn với người dùng cuối giúp giảm độ trễ và cải thiện trải nghiệm của họ.

### Kết luận 

Amazon Web Services (AWS) cung cấp hơn 175 dịch vụ đám mây để đáp ứng mọi nhu cầu có thể. Chúng tôi chỉ mô tả ngắn gọn phần nổi của tảng băng khổng lồ này. Bên cạnh các dịch vụ có mục đích chung, nó còn có hàng chục dịch vụ chuyên biệt hơn về máy học, IoT, Phương tiện và các danh mục khác. Amazon Braket thậm chí còn cho phép bạn thử nghiệm với điện toán lượng tử!

Với các dịch vụ điện toán đám mây như AWS, bạn có thể tập trung vào việc phát triển các ứng dụng của mình mà không phải lo lắng quá nhiều về việc quản lý và thay đổi quy mô máy chủ của mình. Bạn trả tiền cho những gì bạn sử dụng với hầu hết các dịch vụ. Phần lớn trong số chúng được quản lý hoàn toàn, giúp giảm đáng kể tổng chi phí sở hữu bằng cách loại bỏ nhu cầu về những người tận tâm quản lý chúng.

Việc làm cho ứng dụng của bạn có tính khả dụng cao, đáng tin cậy và có khả năng chịu lỗi dễ dàng hơn nhiều trong khi vẫn duy trì hiệu suất vượt trội và mở rộng quy mô trên toàn thế giới.

Chi phí AWS có xu hướng cộng dồn theo số lượng dịch vụ bạn sử dụng. Đối với một công ty khởi nghiệp công nghệ trung bình, họ có thể nhanh chóng đạt đến mức độ khó chịu. May mắn thay, có một tùy chọn để đăng ký khoản tín dụng AWS miễn phí lên tới 10.000 USD từ các đối tác của họ, như FounderPass.com . Đó là một cách tuyệt vời để các công ty khởi nghiệp và nhà sáng lập ở giai đoạn đầu bắt đầu với AWS. Tư cách thành viên của họ chỉ là 99 đô la/năm để truy cập thỏa thuận này. Nhân tiện, chúng tôi không liên kết với họ theo bất kỳ cách nào.

> Tài liệu tham khảo [https://aws.amazon.com/vi/](https://aws.amazon.com/vi/)
