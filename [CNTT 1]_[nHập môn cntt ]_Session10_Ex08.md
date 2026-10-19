# Chữa Lỗi Bảng Đăng Ký Báo Cáo Viên Không Lọc Được

***PHẦN 1: BẢNG BỊ LỖI GÌ?***

- Dùng Merge Cell ở tiêu đề & có hàng trống: Làm bộ lọc AutoFilter bị ngắt quãng, không quét được hết bảng.

- Dòng "TỔNG SỐ" nằm chen giữa bảng: Cắt đứt dữ liệu, khiến bộ lọc dừng lại sớm.

-  Chữ bị thừa khoảng trắng: Khiến máy tính hiểu nhầm là 2 giá trị khác nhau nên lọc thiếu.

***PHẦN 2: CÁCH SỬA***

- Công thức làm sạch dữ liệu:Tạo cột phụ bên cạnh cột B, tại ô C6 (hoặc hàng tương ứng) gõ:$$\text{=TRIM(B6)}$$

- Chọn toàn bộ bảng dữ liệu chuẩn $\rightarrow$ Nhấn Ctrl + Shift + L để bật AutoFilter.Tại cột Khoa / Viện: Tích chọn chỉ lọc CNTT.Tại cột Điểm Xét Duyệt: Chọn Number Filters $\rightarrow$ Greater Than Or Equal To... (Lớn hơn hoặc bằng) $\rightarrow$ Nhập 8.0 $\rightarrow$ Bấm OK.