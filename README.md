# DTH235659 - Nguyễn Phi Hùng

Thông tin sinh viên
- Họ và tên: Nguyễn Phi Hùng
- Mã số sinh viên (MSSV): DTH235659

Khóa học
- Môn: Lập trình Python
- Trường: Đại học An Giang

Mô tả repository
-----------------
Kho này chứa các bài tập / ví dụ thực hành cho môn Lập trình Python. Mỗi chương/bài được tổ chức trong thư mục `chuong_1`, `chuong_2`, ... đến `chuong_7`. File `data.txt` là dữ liệu mock dùng trong một vài bài tập (sản phẩm, danh mục).

Cấu trúc chính
- `data.txt` - mock data JSON (danh mục, sản phẩm) sử dụng bởi một số bài tập.
- `chuong_1/` … `chuong_7/` - mã nguồn bài tập theo từng chương.
- `README.md` - tài liệu này.

Yêu cầu & môi trường
- Python 3.8+ (khuyến nghị 3.10+)
- Không có thư viện bên ngoài đặc biệt; nếu cần, sẽ chỉ ra trong từng bài.

Cách chạy ví dụ nhanh
1. Mở terminal (bash) tại thư mục gốc của repository.
2. Chạy một file ví dụ, ví dụ chạy demo trong `chuong_7/cau_9.py`:

```bash
python "d:\Project\Code\Python\DTH235659_NguyenPhiHung_NOPBAI\chuong_7\cau_9.py"
```

Ghi chú khi làm bài tập (lưu ý cộng tác)
- Tránh xung đột ID hoặc dữ liệu mock với các bạn trong nhóm: nếu cần, hãy cập nhật các mã (ví dụ `DM01`, `SP01`) thành mã cá nhân hóa trước khi commit.
- Khi chỉnh sửa `data.txt` hoặc file chung, kiểm tra kỹ `git status`/`git diff` trước khi commit.
- Nếu cần cố định cách merge cho `data.txt` (ví dụ để luôn giữ phiên bản local), tham khảo `.gitattributes` với rule `merge=ours`.

Liên hệ
- Nếu cần trao đổi trực tiếp về bài tập hoặc có vấn đề về repo, thêm thông tin liên hệ hoặc mở issue trên GitHub.

Chúc học tốt!
