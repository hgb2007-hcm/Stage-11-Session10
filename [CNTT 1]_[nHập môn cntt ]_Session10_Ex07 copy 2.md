# Gỡ Lỗi Tài Liệu Kế Hoạch Hội Nghị Khoa Học Sinh Viên

## PHẦN 1: PHÂN TÍCH LỖI

**Nguyên Nhân**:

**Cơ chế:** Auto TOC chỉ tìm và quét các đoạn văn bản được gán nhãn Heading 1, 2, 3...

**Lỗi:** Tất cả 7 dòng tiêu đề đều đang mang nhãn Normal (văn bản thường), dù đã được chỉnh chữ to hay tô màu thủ công. Vì không có nhãn Heading nào, Word báo mục lục rỗng.

**Hậu Quả:**

Trong Auto TOC, mỗi cấp Heading tương ứng với một mức thụt lùi đầu dòng (Indentation).

Nếu gán nhầm H2 thành H3, dòng đó sẽ bị thụt lùi quá sâu vào trong, làm sai lệch thứ bậc logic và cấu trúc phân cấp thông tin của tài liệu.

***Phần 2: Sửa lỗi & Nghiệm thu***
Bôi đen dòng $\rightarrow$ Bấm phím tắt:Ctrl + Alt + 1 (Heading 1): 1. Thông tin chung hội nghị, 2. Cơ cấu ban tổ chức, 3. Lịch trình sự kiệnCtrl + Alt + 2 (Heading 2): 1.1. Tên hội nghị, 1.2. Thời gian & địa điểm, 2.1. Ban Nội dungCtrl + Alt + 3 (Heading 3): 2.1.1. Tiểu ban Kỹ thuậtChèn mục lục: Vào References $\rightarrow$ Table of Contents $\rightarrow$ Chọn mẫu tự động.

- Mục lục không tự đổi số trang

- Sửa: Click vào mục lục $\rightarrow$ Bấm phím F9 $\rightarrow$ Chọn Update page numbers only $\rightarrow$ Bấm OK.