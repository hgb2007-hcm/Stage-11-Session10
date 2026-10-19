# Chuẩn hóa quy trình tra cứu dữ liệu kho hàng

 ***PHẦN 1: PHÂN TÍCH 4 THAM SỐ CỦA HÀM VLOOKUP***

 **Cú pháp chuẩn của hàm VLOOKUP:**

=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])

- lookup_value: Ô chứa Mã linh kiện ở sheet Don_Hang (ví dụ ô A2 của sheet Don_Hang).
- table_array: Là bảng dữ liệu tham chiếu nằm ở sheet "Danh_Muc"
- col_index_num: Số thứ tự cột lấy dữ liệu
- range_lookup : Chế độ tìm kiếm 

***Phần 2: CÔNG THỨC HOÀN CHỈNH***

***Công thức lấy Tên linh kiện***
- =IFERROR(VLOOKUP(A2, Danh_Muc!$A$2:$C$100, 2, FALSE), "Không tìm thấy mã")

***Công thức tối ưu***
- =IFERROR(VLOOKUP(TRIM(A2), Danh_Muc!$A$2:$C$100, 2, FALSE), "Không tìm thấy mã")

 ***Công thức lấy đơn giá***
 
 - =IFERROR(VLOOKUP(TRIM(A2), Danh_Muc!$A$2:$C$100, 3, FALSE), 0)