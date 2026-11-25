# QLDACNTT1
Website quản lý cửa hàng tiện lợi, hỗ trợ quản lý sản phẩm, danh mục, nhà cung cấp, nhập hàng, bán hàng, kho hàng, nhân viên, khách hàng và thống kê doanh thu. Xây dựng bằng PHP, MySQL, HTML, CSS, JavaScript và Bootstrap.

# DỰ ÁN QUẢN LÝ CỬA HÀNG TIỆN LỢI

## 1. Giới thiệu dự án

**Tên dự án:** Hệ thống quản lý cửa hàng tiện lợi (Convenience Store Management System).

Dự án được xây dựng nhằm phát triển một hệ thống phần mềm hỗ trợ quản lý và vận hành các hoạt động kinh doanh của cửa hàng tiện lợi. Hệ thống giúp số hóa các nghiệp vụ quản lý hàng hóa, sản phẩm, nhập hàng, bán hàng, nhân viên, khách hàng và doanh thu.

Thông qua hệ thống, người quản lý có thể theo dõi tình hình hoạt động của cửa hàng một cách tập trung, trong khi nhân viên có thể thực hiện các nghiệp vụ bán hàng và tra cứu thông tin nhanh chóng, thuận tiện.

Dự án hướng đến việc ứng dụng kiến thức về phân tích thiết kế hệ thống, lập trình web, quản lý cơ sở dữ liệu và làm việc nhóm vào giải quyết một bài toán thực tế.

## 2. Mục tiêu dự án

### 2.1. Mục tiêu tổng quát

Xây dựng một hệ thống quản lý cửa hàng tiện lợi có giao diện thân thiện, dễ sử dụng và đáp ứng được các nghiệp vụ quản lý cơ bản. Hệ thống giúp tối ưu hóa quy trình vận hành, giảm thiểu sai sót trong quá trình quản lý thủ công, tiết kiệm thời gian và nâng cao hiệu quả kinh doanh.

### 2.2. Mục tiêu cụ thể

Dự án tập trung vào các mục tiêu sau:

- **Quản lý sản phẩm:** Thêm, sửa, xóa, tìm kiếm và cập nhật thông tin sản phẩm như mã sản phẩm, tên sản phẩm, danh mục, giá bán và số lượng tồn kho.
- **Quản lý danh mục:** Phân loại sản phẩm theo từng nhóm hàng để thuận tiện cho việc tìm kiếm và quản lý.
- **Quản lý nhà cung cấp:** Lưu trữ và quản lý thông tin các nhà cung cấp hàng hóa.
- **Quản lý nhập hàng:** Theo dõi thông tin phiếu nhập, số lượng nhập, giá nhập và nhà cung cấp.
- **Quản lý bán hàng:** Hỗ trợ nhân viên lập hóa đơn, tính tổng tiền và lưu trữ thông tin giao dịch.
- **Quản lý kho:** Theo dõi số lượng hàng tồn kho, cập nhật số lượng sau khi nhập và bán hàng.
- **Quản lý nhân viên:** Lưu trữ thông tin nhân viên và quản lý tài khoản đăng nhập.
- **Quản lý khách hàng:** Lưu trữ, cập nhật và tra cứu thông tin khách hàng.
- **Quản lý tài khoản và phân quyền:** Kiểm soát quyền truy cập và chức năng sử dụng của từng đối tượng.
- **Thống kê và báo cáo:** Tổng hợp doanh thu, số lượng hóa đơn, tình hình nhập hàng và tồn kho để hỗ trợ người quản lý đưa ra quyết định.

### 2.3. Ý nghĩa của dự án

- Giúp cửa hàng quản lý hoạt động kinh doanh một cách khoa học và hiệu quả.
- Hạn chế sai sót khi quản lý dữ liệu bằng phương pháp thủ công.
- Tăng tốc độ xử lý các nghiệp vụ bán hàng và nhập hàng.
- Hỗ trợ kiểm soát hàng hóa và tình trạng tồn kho.
- Cung cấp dữ liệu thống kê phục vụ việc đánh giá tình hình kinh doanh.
- Giúp các thành viên vận dụng kiến thức lập trình và kỹ năng làm việc nhóm vào một sản phẩm thực tế.

## 3. Đối tượng sử dụng hệ thống

Hệ thống hướng đến các đối tượng sử dụng chính:

| Đối tượng | Mô tả |
|---|---|
| Quản trị viên (Admin) | Quản lý tài khoản, phân quyền và kiểm soát toàn bộ hệ thống. |
| Quản lý cửa hàng (Manager) | Theo dõi hoạt động kinh doanh, quản lý hàng hóa, nhân viên và xem báo cáo. |
| Nhân viên (Staff) | Thực hiện bán hàng, lập hóa đơn và tra cứu thông tin sản phẩm. |

## 4. Các chức năng chính

| STT | Chức năng | Mô tả |
|---|---|---|
| 1 | Đăng nhập, đăng xuất | Xác thực tài khoản người dùng. |
| 2 | Quản lý tài khoản | Thêm, sửa, xóa và phân quyền tài khoản. |
| 3 | Quản lý sản phẩm | Quản lý thông tin và giá bán sản phẩm. |
| 4 | Quản lý danh mục | Phân loại sản phẩm theo nhóm hàng. |
| 5 | Quản lý nhà cung cấp | Lưu trữ thông tin nhà cung cấp. |
| 6 | Quản lý nhập hàng | Lập phiếu nhập và cập nhật hàng hóa. |
| 7 | Quản lý bán hàng | Lập hóa đơn và xử lý giao dịch bán hàng. |
| 8 | Quản lý kho | Theo dõi số lượng hàng tồn kho. |
| 9 | Quản lý nhân viên | Quản lý thông tin nhân viên. |
| 10 | Quản lý khách hàng | Lưu trữ thông tin khách hàng. |
| 11 | Thống kê, báo cáo | Theo dõi doanh thu và tình hình kinh doanh. |

## 5. Công nghệ sử dụng

Các công nghệ dự kiến sử dụng trong quá trình phát triển dự án:

- **Frontend:** HTML, CSS, JavaScript, Bootstrap.
- **Backend:** PHP.
- **Database:** MySQL.
- **Công cụ phát triển:** Visual Studio Code.
- **Quản lý mã nguồn:** Git và GitHub.
- **Môi trường chạy:** XAMPP.

*Lưu ý: Điều chỉnh danh sách công nghệ theo đúng công nghệ thực tế mà nhóm sử dụng.*

## 6. Vai trò và phân công nhiệm vụ các thành viên

Các thành viên trong nhóm được phân công nhiệm vụ dựa trên năng lực và yêu cầu của dự án. Mỗi thành viên chịu trách nhiệm đối với phần công việc được giao và phối hợp với các thành viên khác để hoàn thành sản phẩm chung.

| STT | Thành viên | Vai trò | Nhiệm vụ |
|---|---|---|---|
| 1 | [Tên thành viên 1] | Nhóm trưởng (Team Leader) | Lập kế hoạch, phân chia công việc, theo dõi tiến độ, điều phối hoạt động nhóm và tổng hợp sản phẩm. |
| 2 | [Tên thành viên 2] | Phân tích nghiệp vụ (Business Analyst) | Thu thập yêu cầu, phân tích nghiệp vụ cửa hàng tiện lợi, xác định chức năng và xây dựng tài liệu phân tích hệ thống. |
| 3 | [Tên thành viên 3] | Thiết kế giao diện (Frontend Developer) | Thiết kế và xây dựng giao diện website, đảm bảo tính trực quan, thân thiện và dễ sử dụng. |
| 4 | [Tên thành viên 4] | Lập trình Backend (Backend Developer) | Xây dựng các chức năng xử lý nghiệp vụ, kết nối cơ sở dữ liệu và xử lý dữ liệu từ giao diện. |
| 5 | [Tên thành viên 5] | Thiết kế cơ sở dữ liệu (Database Developer) | Phân tích dữ liệu, thiết kế bảng, xây dựng quan hệ giữa các bảng và tối ưu truy vấn cơ sở dữ liệu. |
| 6 | [Tên thành viên 6] | Kiểm thử và tài liệu (Tester/Documentation) | Kiểm thử chức năng, phát hiện lỗi, ghi nhận kết quả kiểm thử và hoàn thiện tài liệu hướng dẫn, README. |

### 6.1. Trách nhiệm chung của các thành viên

Ngoài nhiệm vụ chuyên môn được phân công, tất cả thành viên có trách nhiệm:

- Chủ động hoàn thành công việc đúng thời hạn.
- Thường xuyên trao đổi và cập nhật tiến độ với nhóm.
- Hỗ trợ các thành viên khác khi cần thiết.
- Kiểm tra và rà soát phần công việc của mình trước khi tích hợp.
- Tham gia kiểm thử, sửa lỗi và hoàn thiện sản phẩm.
- Tuân thủ quy trình làm việc và quản lý mã nguồn bằng Git/GitHub.

## 7. Cấu trúc dự án

Cấu trúc thư mục dự kiến:

```text
Convenience-Store-Management/
│
├── public/
│   ├── css/
│   ├── js/
│   └── images/
│
├── app/
│   ├── controllers/
│   ├── models/
│   ├── views/
│   └── services/
│
├── config/
│   └── database.php
│
├── database/
│   └── database.sql
│
├── README.md
└── index.php
```

*Cấu trúc có thể thay đổi tùy theo cách tổ chức mã nguồn thực tế của nhóm.*

## 8. Kết quả mong đợi

Sau khi hoàn thành dự án, nhóm mong muốn đạt được các kết quả:

- Xây dựng được website quản lý cửa hàng tiện lợi với các chức năng cơ bản.
- Quản lý được thông tin sản phẩm, nhân viên, khách hàng và nhà cung cấp.
- Thực hiện được các nghiệp vụ nhập hàng, bán hàng và quản lý tồn kho.
- Hỗ trợ quản lý tài khoản và phân quyền người dùng.
- Hiển thị được các thông tin thống kê và báo cáo kinh doanh.
- Đảm bảo dữ liệu được lưu trữ có tổ chức và hạn chế sai sót.
- Hoàn thiện kỹ năng phân tích, thiết kế, lập trình và làm việc nhóm.

## 9. Hướng dẫn cài đặt và chạy dự án

### Yêu cầu môi trường

- PHP.
- MySQL.
- XAMPP.
- Visual Studio Code.

### Các bước cài đặt

**Bước 1: Clone dự án**

```bash
git clone <repository-url>
```

**Bước 2: Di chuyển dự án**

Đưa thư mục dự án vào thư mục `htdocs` của XAMPP.

**Bước 3: Khởi động môi trường**

Mở XAMPP và khởi động Apache, MySQL.

**Bước 4: Tạo cơ sở dữ liệu**

- Truy cập phpMyAdmin.
- Tạo cơ sở dữ liệu mới.
- Import file `database/database.sql`.

**Bước 5: Cấu hình kết nối**

Cập nhật thông tin kết nối MySQL trong file cấu hình của dự án.

**Bước 6: Chạy dự án**

Truy cập địa chỉ:

```text
http://localhost/Convenience-Store-Management/
```

## 10. Quản lý mã nguồn

Nhóm sử dụng Git và GitHub để quản lý mã nguồn và phối hợp phát triển dự án.

Các thành viên thực hiện:
- Clone repository để làm việc trên máy cá nhân.
- Tạo branch riêng khi phát triển chức năng.
- Commit các thay đổi với nội dung rõ ràng.
- Push code lên GitHub.
- Tạo Pull Request để kiểm tra và hợp nhất mã nguồn.
- Thường xuyên đồng bộ code với nhánh chính để tránh xung đột.
