<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>NT208.O22.ANTT Nhóm 7</title>
  <style>
    h1, h2, h3, h4 {
      text-align: center;
    }
    h1 {
      color: #4CAF50;
    }
    h2 {
      color: #2196F3;
    }
    h3 {
      color: #FF9800;
    }
    h4 {
      color: #9C27B0;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin-bottom: 10px;
    }
    a {
      color: #4CAF50;
    }
    p {
      text-align: center;
    }
  </style>
</head>
<body>
  <h1>NT208.O22.ANTT Nhóm 7</h1>
  <h2>WEBSITE THƯ VIỆN TRỰC TUYẾN</h2>

  <h3>Danh sách thành viên:</h3>
  <ul>
    <li>Nguyễn Bình Khải</li>
    <li>Nguyễn Đức Hoàng</li>
    <li>Hà Minh Nghĩa</li>
    <li>Huỳnh Ngọc Bảo Châu</li>
    <li>Tạ Thúc Trung Kiên</li> 
  </ul>

  <h3>Framework sử dụng:</h3>
  <ul> 
    <li><a href="https://nodejs.org/en/download/">NodeJS</a>: Tải và cài đặt Node.js từ trang chủ.</li>
    <li><a href="https://expressjs.com/">ExpressJS</a>: Tải và cài đặt ExpressJS bằng cách chạy lệnh <code>npm install express</code> trong terminal.</li>
    <li><a href="https://www.mongodb.com/try/download/community">MongoDB</a>: Tải và cài đặt MongoDB từ trang chủ.</li>
  </ul>

  <h3>Hướng dẫn cài đặt:</h3>
  <h4>Cài đặt môi trường:</h4>
  <ul>
    <li>Cài đặt Node.js và MongoDB trên máy tính của bạn.</li>
    <li>Clone repository từ GitHub về máy tính.</li>
    <li>Mở terminal và di chuyển đến thư mục chứa repository đã clone.</li>
    <li>Chạy lệnh <code>npm install</code> để cài đặt các gói phụ thuộc.</li>
  </ul>
  <h4>Triển khai dự án:</h4>
  <ul>
    <li>Mở terminal và di chuyển đến backend: <code>cd backend</code>.</li>
    <li>Dùng lệnh: <code>npm start</code> để bắt đầu deploy.</li>
  </ul>

  <h3>Sơ đồ các chức năng:</h3>
  <p>
    <img src="https://github.com/MNghiazz/Doan/assets/109862700/a9d31d68-1a9d-4323-bcda-86230b856060" alt="Functional Diagram" width="600">
  </p>

  <h3>Các tính năng chính:</h3>
  <ul>
    <li>Quản lý sách: Thêm, sửa, xóa và xem thông tin sách.</li>
    <li>Quản lý người dùng: Đăng ký, đăng nhập và quản lý thông tin cá nhân.</li>
    <li>Tìm kiếm sách: Tìm kiếm sách theo tên, tác giả, thể loại.</li>
    <li>Đánh giá và bình luận sách: Cho phép người dùng đánh giá và bình luận sách.</li>
  </ul>

  <h3>Công nghệ sử dụng:</h3>
  <ul>
    <li>Frontend: HTML, CSS, JavaScript, ReactJS</li>
    <li>Backend: NodeJS, ExpressJS</li>
    <li>Database: MongoDB</li>
    <li>Authentication: JWT (JSON Web Tokens)</li>
  </ul>

  <h3 style="color: #009688;">Trả lời câu hỏi các nhóm:</h3>
  <ul>
    <li>
      <strong>Cơ chế truy vấn trong PostgreSQL, MongoDB và MySQL. Sự khác biệt giữa SQL và NoSQL. Cách tối ưu hoá truy vấn trong CSDL:</strong>
      <ul>
        <li><strong>PostgreSQL và MySQL (SQL):</strong> Cả hai đều sử dụng ngôn ngữ SQL (Structured Query Language) để truy vấn dữ liệu. PostgreSQL hỗ trợ mạnh mẽ các tính năng nâng cao như các loại dữ liệu phong phú, hệ thống quản lý giao dịch phức tạp và khả năng mở rộng. MySQL thường được biết đến với hiệu suất cao và dễ sử dụng.</li>
        <li><strong>MongoDB (NoSQL):</strong> Sử dụng mô hình tài liệu để lưu trữ dữ liệu, không cần bảng và không sử dụng SQL. Truy vấn trong MongoDB được thực hiện thông qua các lệnh và cú pháp của MongoDB.</li>
        <li><strong>Sự khác biệt giữa SQL và NoSQL:</strong> SQL là ngôn ngữ chuẩn dùng cho các cơ sở dữ liệu quan hệ (RDBMS) như PostgreSQL và MySQL, trong khi NoSQL là thuật ngữ chung cho các loại cơ sở dữ liệu không quan hệ như MongoDB. SQL thích hợp cho các hệ thống yêu cầu giao dịch phức tạp và dữ liệu có cấu trúc chặt chẽ, trong khi NoSQL phù hợp với dữ liệu phi cấu trúc hoặc thay đổi cấu trúc nhanh chóng.</li>
        <li><strong>Tối ưu hóa truy vấn:</strong> Sử dụng chỉ số (indexing), phân vùng (partitioning), tối ưu hóa câu lệnh SQL, caching, và điều chỉnh cấu hình hệ thống để cải thiện hiệu suất truy vấn.</li>
      </ul>
    </li>
    <li>
      <strong>Nêu tiêu chí cụ thể để chọn 1 DBMS trong 1 dự án cụ thể:</strong>
      <ul>
        <li><strong>Yêu cầu về tính nhất quán và độ tin cậy:</strong> Nếu dự án yêu cầu tính nhất quán và giao dịch mạnh, RDBMS như PostgreSQL hoặc MySQL là lựa chọn tốt.</li>
        <li><strong>Khả năng mở rộng:</strong> Nếu dự án cần khả năng mở rộng nhanh chóng và xử lý dữ liệu phi cấu trúc, NoSQL như MongoDB là lựa chọn phù hợp.</li>
        <li><strong>Hiệu suất và tốc độ:</strong> Xem xét khối lượng công việc đọc/ghi, tốc độ phản hồi, và khả năng xử lý dữ liệu lớn.</li>
        <li><strong>Chi phí:</strong> Bao gồm chi phí bản quyền phần mềm, chi phí bảo trì và vận hành.</li>
        <li><strong>Đội ngũ kỹ thuật:</strong> Đánh giá kỹ năng và kinh nghiệm của đội ngũ kỹ thuật với các hệ quản trị cơ sở dữ liệu khác nhau.</li>
      </ul>
    </li>
    <li>
      <strong>Khi nào nên dùng SQL và NoSQL:</strong>
      <ul>
        <li><strong>SQL:</strong> Khi dữ liệu có cấu trúc rõ ràng, yêu cầu tính nhất quán cao, và cần hỗ trợ các giao dịch phức tạp.</li>
        <li><strong>NoSQL:</strong> Khi dữ liệu phi cấu trúc, cần khả năng mở rộng linh hoạt, hoặc khi ứng dụng yêu cầu xử lý dữ liệu theo thời gian thực.</li>
      </ul>
    </li>
    <li>
      <strong>Những dự án lớn người ta dùng DB nào:</strong>
      <ul>
        <li><strong>SQL:</strong> Các hệ thống tài chính, ngân hàng, quản lý doanh nghiệp, và các hệ thống cần tính nhất quán dữ liệu cao như PostgreSQL, MySQL.</li>
        <li><strong>NoSQL:</strong> Các hệ thống mạng xã hội, phân tích dữ liệu lớn, IoT, và các ứng dụng cần xử lý dữ liệu phi cấu trúc như MongoDB, Cassandra.</li>
      </ul>
    </li>
    <li>
      <strong>Cách sử dụng SQL trong các ứng dụng thực tế như thế nào:</strong>
      <ul>
        <li><strong>Thiết kế và quản lý cơ sở dữ liệu:</strong> Tạo bảng, định nghĩa quan hệ, và thiết lập chỉ số.</li>
        <li><strong>Truy vấn và xử lý dữ liệu:</strong> Sử dụng câu lệnh SELECT, INSERT, UPDATE, DELETE để quản lý và thao tác dữ liệu.</li>
        <li><strong>Tối ưu hóa hiệu suất:</strong> Sử dụng các kỹ thuật tối ưu hóa truy vấn và cấu hình hệ thống.</li>
        <li><strong>Tích hợp với các ứng dụng:</strong> Sử dụng ORM (Object-Relational Mapping) hoặc trực tiếp tương tác với cơ sở dữ liệu qua các ngôn ngữ lập trình.</li>
      </ul>
    </li>
    <li>
      <strong>Sự khác biệt giữa SQL và NoSQL:</strong>
      <ul>
        <li><strong>SQL:</strong> Dữ liệu được lưu trữ trong các bảng, có cấu trúc rõ ràng, và các bảng có quan hệ với nhau. SQL sử dụng các câu lệnh chuẩn hóa để truy vấn và thao tác dữ liệu.</li>
        <li><strong>NoSQL:</strong> Dữ liệu có thể được lưu trữ dưới dạng tài liệu, đồ thị, hoặc cặp key-value, không có cấu trúc cố định, và không yêu cầu schema. NoSQL có thể mở rộng linh hoạt hơn và xử lý tốt hơn các dữ liệu phi cấu trúc.</li>
      </ul>
    </li>
  </ul>

  <h3 style="color: #009688;">Liên hệ:</h3>
  <ul>
    <li>Email: </li>
    <li>GitHub: <a href=""></a></li>
    <li>Facebook: <a href=""></a></li>
  </ul>
</body>
</html>
```

In this code, the new section "Trả lời câu hỏi các nhóm" includes the provided questions and answers in a nested list format for clarity and organization.
