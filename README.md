# Quản lý Đảng viên PTIT

Ứng dụng quản lý Đảng viên dành riêng cho Đảng ủy Học viện Công nghệ Bưu chính Viễn thông (PTIT).

## Tách biệt môi trường

- Repository này dành riêng cho sản phẩm Quản lý Đảng viên.
- Dùng database, tài khoản database, secrets, seed và dữ liệu lưu trữ riêng; không tái sử dụng cấu hình hoặc dữ liệu của ứng dụng Đoàn viên.
- Sao chép `.env.example` thành `.env` và điền thông tin môi trường cục bộ. Không commit `.env` hoặc secrets.
- `storage/` là vùng lưu tệp cục bộ riêng khi phát triển; không đặt dữ liệu thật trong Git.

## Trạng thái

Repository mới đang ở giai đoạn chuẩn bị. Chưa có mã ứng dụng hoặc cấu hình kết nối dịch vụ.

## Quy ước Git

- Nhánh chính: `main`.
- Nhánh công việc: `codex/<ten-cong-viec>` hoặc `<loai>/<ten-cong-viec>`.
- Không push cho đến khi cấu hình và xác minh remote riêng của repository này.
