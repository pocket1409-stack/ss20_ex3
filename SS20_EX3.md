
Thiết kế quy trình sử dụng Backup Codes để lấy lại quyền truy cập mà không làm lộ thông tin cho kẻ nhặt được điện thoại.

**Thành phần**

**Chi xử lý lý**

**Đầu vào**


  • 01 **Code dự phòng** (mã dự phòng) lưu ngoại tuyến.

**Quá trình**

1. **Xác thực:** Đăng nhập AWS bằng Mã dự phòng thay cho OTP.

  

2. **Hủy bỏ mã cũ:** Truy cập , xóa liên kết cũ và hủy bỏ cũ Mã dự phòng.

  

3. **Cấp độ mới:** Cấu hình trên máy chủ mới và sinh bộ Mã dự phòng mới.

**Đầu ra**

• Khôi phục quyền quản trị  an toàn.

  
• Chặn triệt để nguy cơ truy cập cơ sở dữ liệu từ thiết bị bị mất.

### Tại sao không lưu Mã dự phòng dưới dạng ảnh trong điện thoại?

1.  **Rò rỉ qua đám mây (Cloud Sync):** Thư viện ảnh tự động đồng bộ lên Google Photos/iCloud. Lộ tài khoản đám mây đồng nghĩa với việc hiển thị toàn bộ bộ mã dự phòng.
    
2.  **Không thể mã hóa chuyên nghiệp:** Ảnh lưu trong máy không được bảo vệ bằng mã hóa cao cấp tiêu chuẩn . 
    
3.  **Quét OCR tự động:** AI và công nghệ nhận dạng chữ trên điện thoại sẽ tự động phân tích hình ảnh thành văn bản, làm cho cảm biến dữ liệu dễ dàng được trích xuất và tìm kiếm.
