# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Phạm Hoàng Hải  
**MSSV:** 1871020214  
**Lớp/Nhóm:** CNTT 18-02  

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Cơ sở dữ liệu bảng điểm sinh viên  
- Asset 2: Tài khoản giảng viên / admin  
- Asset 3 (nếu có): Hệ thống server lưu trữ dữ liệu  

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Confidentiality (Rò rỉ thông tin, lộ điểm sinh viên)  
- Sự cố B -> Integrity (Bị sửa điểm trái phép)  
- Sự cố C -> Availability (Hệ thống bị sập, không truy cập được)  

---

## 3. Phân tích sự cố B

- Threat: Hacker hoặc người dùng nội bộ chỉnh sửa trái phép dữ liệu điểm  

- Vulnerability:  
  - Không kiểm tra quyền truy cập chặt chẽ  
  - Mật khẩu yếu / dùng chung tài khoản  
  - Không có log theo dõi thay đổi  

- Mitigation:  
  - Áp dụng phân quyền (RBAC)  
  - Mã hóa và xác thực mạnh (2FA)  
  - Ghi log và audit hệ thống  
  - Backup dữ liệu thường xuyên  

---

## 4. Reflection
Qua bài lab này, em hiểu rõ hơn về mô hình CIA trong an ninh thông tin và cách áp dụng vào hệ thống thực tế. Việc xác định assets giúp nhận diện những gì cần bảo vệ quan trọng nhất. Khi phân tích các sự cố theo CIA, em thấy rõ mỗi loại tấn công sẽ ảnh hưởng đến các khía cạnh khác nhau của hệ thống. Đặc biệt, việc xác định threat, vulnerability và mitigation giúp em hiểu rõ cách hệ thống bị tấn công và cách phòng chống hiệu quả. Đây là kiến thức quan trọng để xây dựng hệ thống an toàn hơn trong tương lai.

---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:  
FIT4012{A-C-B-I-C-A}
