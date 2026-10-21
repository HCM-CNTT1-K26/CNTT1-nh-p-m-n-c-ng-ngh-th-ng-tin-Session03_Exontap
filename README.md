# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session03_EXontap
## Phần 1 — Kiến trúc Hệ điều hành

1. **Đa nhiệm:** Quản lý tiến trình & bộ nhớ. CPU chia sẻ thời gian (Time-sharing) và cấp phân vùng RAM riêng biệt nên không xung đột.
2. **Shell vs Kernel:** Qua **Shell** trước. Shell tiếp nhận lệnh, dịch sang Kernel. Không tương tác trực tiếp Kernel vì Kernel chạy ở chế độ đặc quyền (Kernel Mode) để bảo vệ phần cứng hệ thống.

## Phần 2 — Cây thư mục & Ổ đĩa

1. Root: `D:\` | Parent của `anh 1.jpg`: `Hinh anh` | Vai trò file: Lá.
2. Lưu Desktop/Downloads nguy hiểm vì dễ mất dữ liệu khi cài lại Win và giới hạn dung lượng/rác hệ thống. Nên lưu ở ổ đĩa dữ liệu riêng (ổ D:).

## Phần 3 — Đường dẫn Path

1. `D:\Nam1\HocKy1\MonHoc\CongNgheThongTin\BaiTapLon\Session02\BaoCaoCuoiKy\Chuong1\Hinh anh\anh 1.jpg`
2. `assets/logo.png`. Không phụ thuộc ổ đĩa hay thư mục gốc của máy khác, chỉ cần giữ nguyên cấu trúc thư mục bên trong.

## Phần 4 — Quy tắc Đặt tên chuẩn

1. `bao-cao-bai-tap-lon-it101-v2.docx`

## Phần 5 — Tổ chức & Dọn dẹp Ổ đĩa

1. Hiện tại: 9 cấp (sai quy tắc). Thiết kế lại theo 4 Trụ Cột & 3 Cấp:
`D:\01_HocTap\IT101\BaiTapLon\anh-1.jpg`

## Phần 6 — Đuôi file & File ẩn

1. **Bẫy:** Đuôi giả mạo ẩn sau tên file (double extension). Tên thật có thể là `de-thi-dap-an.pdf.exe`.
**Cách phát hiện:** Mở File Explorer -> Tab **View** -> Tích chọn **File name extensions**.
