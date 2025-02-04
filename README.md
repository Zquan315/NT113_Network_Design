# **NT113_Network_Design**

## 1. Thành viên thực hiện
  + [TÔ CÔNG QUÂN](https://github.com/Zquan315)

## 2. Tổng quan
  * Đây là đồ án môn học **Thiết kế mạng - Design network - NT118**
  * **Tên đề tài:** Thiết kế hệ thống mạng công ty - Design a company network system
  * **Mục tiêu:** Xây dựng được một hệ thống mạng cho một công ty có hai trụ sở. Trụ sở chính được đặt tại Thủ Đức, TP. Hồ Chí Minh và một trụ sở phụ (chi nhánh) tại Quận 3, TP. Hồ Chí Minh.
  * **Tổng quan**: Công ty Outsource O-UIT có 1 trụ sở chính tại Thủ Đức và một chi nhánh tại Quận 3. Trụ sở chính là một tòa nhà 5 tầng gồm Data Center và các văn phòng làm việc dành cho CEO, HR, Project manager, Technical Manager, Business Analyst, IT manager và các nhóm developer và tester cho các project thuộc thị trường nước ngoài. Chi nhánh tại Quận 3 là văn phòng làm việc của các nhóm developer và tester cho các project thuộc thị trường trong nước.
  * **Các thông tin cơ bản về đề tài (yêu cầu khách hàng):**

| **Trụ sở chính**                         | **Chi nhánh**                                                             |
|------------------------------------|---------------------------------------------------------------------------|
| Developer và Tester chỉ được sử dụng máy bàn tại công ty, không được sử dụng laptop riêng để truy cập vào mạng của công ty. | Developer và Tester chỉ được sử dụng máy bàn tại công ty, không được sử dụng laptop riêng để truy cập vào mạng của công ty                         |
| CEO, HR, Project manager, Technical Manager, Business Analyst, IT manager được sử dụng Laptop, truy cập vào hệ thống wifi nội bộ sử dụng tài khoản xác thực.              | Sử dụng kết nối VPN site-to-site để deploy ứng dụng lên hệ thống tại Data Center                                                   |
| Một hệ thống wifi public với đường kết nối Internet riêng.                    | Một hệ thống wifi với đường kết nối Internet riêng                              |
| Hệ thống phần cứng để triển khai hệ thống server ảo phục vụ cho việc deploy các ứng dụng trong giai đoạn test.               |                       |
| Sử dụng các dịch vụ Cloud deploy các ứng dụng trong giai đoạn staging để khách hàng sử dụng thử trước khi đưa ra thực tế.             |                         |
                                                                          

## 3. Sơ đồ mạng Logic


> <span style="color:red;">**Copyright by To Cong Quan**</span> 
