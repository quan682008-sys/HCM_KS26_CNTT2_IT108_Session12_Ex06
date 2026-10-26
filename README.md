# HCM_KS26_CNTT2_IT108_Session12_Ex06
##  Phần 1. Phân tích: Bảng Excel xấu và đúng chuẩn

| Tiêu chí | Bảng Excel xấu | Bảng Excel đúng |
|---|---|---|
| Tiêu đề | Gộp nhiều ô (Merge Cell) | Một hàng tiêu đề duy nhất |
| Field (cột) | Trộn giá, mã, tỷ lệ | Mỗi cột chứa một loại dữ liệu |
| Record (hàng) | Có hàng trống xen kẽ | Mỗi hàng là một bất động sản |
| Công thức | Nhập kết quả thủ công | Tự tính toán bằng công thức |
| Tra cứu | Vùng dữ liệu bị trôi | Cố định vùng bằng dấu $ |

---

## Phần 3. Kiểm thử

Cách dùng dấu $ là: `$G$4:$I$9` (quét hết từ G4 đến I9), sẽ không làm cho bị nhảy ô khi quét.

Nếu không có $ thì những tên trùng nhau có thể hiện lỗi `#N/A` vì dữ liệu của nó nằm ngoài khoảng mà VLOOKUP quét.
