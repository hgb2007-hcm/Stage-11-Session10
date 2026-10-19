# Chuẩn hóa quy trình tuyển dụng cho Startup

***Phần 1 (Thiết kế Kiến trúc)***

 [INPUT: Nộp Hồ Sơ] ──> [PROCESS: Sàng Lọc & Filter] ──> [OUTPUT:
  Thư Mời Phỏng Vấn]

  ### Input (Đầu vào)
* **Dữ liệu ứng viên:** Thu thập thông tin từ CV / Google Form.
* **Các trường dữ liệu cơ bản:** Mã ƯV, Họ tên, Email, SĐT, Vị trí ứng tuyển, Điểm chuyên môn (thang 10), Kỹ năng ngoại ngữ, Trạng thái.



### Process (Xử lý dữ liệu)
* **Chuẩn hóa Database (5 Quy tắc vàng Excel):**
  1. Hàng 1 làm Tiêu đề (Header), tuyệt đối không Merge ô.
  2. Không bỏ trống dòng/cột giữa chừng.
  3. Đúng kiểu dữ liệu (Điểm = Số, Ngày = YYYY-MM-DD).
  4. Mỗi cột 1 loại thông tin (Họ tên không dính chung với SĐT).
  5. Mỗi dòng đại diện 1 ứng viên duy nhất.
* **Lọc tự động (Filter):**
  * Điểm chuyên môn > 8.
  * Ngoại ngữ: Khác "Không".



### Output (Đầu ra)
* **Danh sách Shortlist:** Các ứng viên thỏa mãn 2 điều kiện lọc.
* **Xuất thư mời (Mail Merge):** Ghép danh sách lọc ở Excel vào các nhãn (`<<Ho_Ten>>`, `<<Vi_Tri>>`, `<<Ngay_Phong_Van>>`) trong mẫu Word để tự động tạo thư mời phỏng vấn.

***Phần 2: Sản Phẩm***

# Liên Đoàn Bóng Đá Thành Phố Hồ Chí Minh  
*30 đường Nguyễn Kim Phường Diên Hồng TPHCM*  
*Email: HFF@gmail.com | Hotline: 123456789*

---

## THƯ MỜI THAM GIA PHỎNG VẤN TUYỂN DỤNG
**Vị trí:** `<<Vi_Tri_Ung_Tuyen>>`

Kính gửi anh/chị **`<<Ho_Ten>>`**,

Lời đầu tiên, Bộ phận Tuyển dụng Liên Đoàn Bóng Đá Thành Phố Hồ Chí Minh xin gửi lời cảm ơn chân thành đến anh/chị vì đã quan tâm và nộp hồ sơ ứng tuyển vào vị trí **`<<Vi_Tri_Ung_Tuyen>>`**.

Sau khi xem xét và đánh giá hồ sơ năng lực (Điểm chuyên môn: **`<<Diem_Chuyen_Mon>>/10`** | Trình độ ngoại ngữ: **`<<Ngoai_Ngu>>`**), chúng tôi rất ấn tượng với những kinh nghiệm và kỹ năng của anh/chị. Công ty trân trọng kính mời anh/chị tham dự buổi phỏng vấn trao đổi trực tiếp với chi tiết như sau:

| Thông tin | Chi tiết |
| :--- | :--- |
| **Thời gian phỏng vấn:** | 09:00 AM, Ngày `<<Ngay_Phong_Van>>` |
| **Hình thức phỏng vấn:** | Trực tiếp tại văn phòng Công ty |
| **Địa điểm:** | Phòng họp, 30 đường Nguyễn Kim Phường Diên Hồng TPHCM |
| **Người phỏng vấn:** | Trưởng phòng Kỹ thuật (Technical Lead) & Trưởng phòng HR |

Anh/Chị vui lòng phản hồi lại email này hoặc liên hệ hotline Tuyển dụng trước 17:00 ngày **`<<Ngay_Xac_Nhan>>`** để xác nhận khả năng tham dự buổi phỏng vấn.

Nếu cần hỗ trợ thêm thông tin hoặc thay đổi lịch phỏng vấn, xin vui lòng liên hệ qua Email: hff@gmail.com hoặc SĐT: 0901 234 567.

**TRÂN TRỌNG,**  
*BỘ PHẬN TUYỂN DỤNG - Liên Đoàn Bóng Đá Thnh Phố Hồ Chí Minh 