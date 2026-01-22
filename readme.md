
> ⚠️ **Lưu ý**
> - Đây là thông tin test do VNPay cung cấp  
> - Chỉ dùng cho mục đích học tập / demo  
> - Không sử dụng cho môi trường thực tế  

---

## 📧 Vé điện tử & QR Code
- Sau khi thanh toán thành công:
  - Hệ thống gửi email xác nhận
  - Email bao gồm:
    - Thông tin phim & lịch chiếu
    - Ghế đã chọn
    - Đồ ăn, thức uống đã đặt
    - **Mã QR để check-in**

- Staff sử dụng QR để:
  - Xác nhận vé hợp lệ
  - In vé giấy cho khách

---

## 🧱 Công nghệ sử dụng

- **Backend**: PHP (MVC)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL
- **Thanh toán**: VNPay Sandbox
- **Email**: PHPMailer (SMTP)
- **QR Code**: Thư viện tạo và quét QR

---

## 👥 Phân quyền hệ thống

| Vai trò | Quyền hạn |
|------|---------|
| Khách hàng | Đặt vé, thanh toán, nhận QR |
| Staff | Quét QR, check-in, in vé |
| Admin | Quản lý toàn bộ hệ thống |

---

## ⚙️ Hướng dẫn cài đặt

1. Clone source code về máy
2. Import file database `.sql`
3. Cấu hình:
   - Kết nối database
   - SMTP Email
   - VNPay Sandbox
4. Chạy project bằng:
   - XAMPP / Laragon
   - Hoặc hosting hỗ trợ PHP

---

## 📌 Ghi chú
- Website phục vụ **mục đích học tập & demo**
- Thanh toán chỉ mang tính **mô phỏng**
- Chưa sử dụng cho mục đích thương mại

---

## 👨‍💻 Tác giả
Sinh viên thực hiện đồ án  
📚 Mục tiêu: Học tập & nghiên cứu hệ thống bán vé trực tuyến

---
