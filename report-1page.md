# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Student grade database
- Login credentials
- 

**CIA mapping:**
- Sự cố A → Confidentiality (lộ điểm sinh viên cho người không có quyền)
-Sự cố B → Integrity (điểm bị sửa trái phép)
-Sự cố C → Availability (hệ thống bị sập, không truy cập được)

**Phân tích sự cố B:**
- Threat: Hacker hoặc sinh viên truy cập trái phép để thay đổi điểm.
- Vulnerability:
 Mật khẩu yếu hoặc bị lộ
 Không có phân quyền rõ ràng
 Thiếu cơ chế kiểm tra/ghi log thay đổi
- Mitigation:
  Sử dụng xác thực mạnh (mật khẩu + OTP)
  Phân quyền rõ ràng (chỉ giảng viên được sửa điểm)
  Ghi log và kiểm tra lịch sử chỉnh sửa
  Mã hóa dữ liệu quan trọng

### 4. Kết luận ngắn
(4-6 dòng: em học được gì từ bài lab này, phần nào khó nhất, điều gì cần chú ý khi phân tích một sự cố an toàn thông tin.)
Qua bài lab này, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào hệ thống thực tế. Em nhận ra rằng mỗi sự cố đều có thể liên quan đến nhiều yếu tố bảo mật khác nhau. Phần khó nhất là phân biệt rõ threat và vulnerability vì chúng dễ bị nhầm lẫn. Khi phân tích an toàn thông tin, cần xác định đúng tài sản và suy nghĩ theo góc nhìn của kẻ tấn công để đưa ra biện pháp phù hợp.
