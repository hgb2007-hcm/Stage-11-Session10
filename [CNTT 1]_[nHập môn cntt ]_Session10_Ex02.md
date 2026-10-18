# Khắc phục sự cố dữ liệu trong kho thiết bị IoT

## PHẦN 1: PHÂN TÍCH LỖI
**Có 3 lỗi:**

- Vi phạm quy tắc "Không dùng Merge Cell ở hàng tiêu đề": Dẫn đến việc nút AutoFilter bị ngắt quãng, biến mất ngay giữa bảng.

- Vi phạm quy tắc "Không để hàng trống (Blank Rows) trong vùng dữ liệu": Làm cho Excel hiểu nhầm là bảng dữ liệu đã kết thúc tại hàng trống đó, khiến tính năng lọc không quét được toàn bộ bảng bên dưới.
- Vi phạm quy tắc "Tính đồng nhất của dữ liệu (Data Integrity)": Dữ liệu bị dính khoảng trắng vô hình (ví dụ: "hỏng " khác với "hỏng"), làm phần mềm chia thành 2 nhóm khác nhau khi lọc.

## PHẦN 2: SỬA LỖI 
- Bỏ Merge Cell: Bôi đen tiêu đề $\rightarrow$ Chọn Merge & Center để gỡ gộp.Xóa dòng trống: Chọn và xóa hết các hàng trống nằm giữa bảng.

- Xóa khoảng trắng thừa: Tại cột phụ bên cạnh, gõ "=TRIM" $\rightarrow$ Kéo xuống hết bảng.Đè lại dữ liệu: Copy cột phụ $\rightarrow$ Paste Values quay lại cột chính $\rightarrow$ Xóa cột phụ.Bật bộ lọc: Bôi đen toàn bảng $\rightarrow$ Nhấn Ctrl + Shift + L.