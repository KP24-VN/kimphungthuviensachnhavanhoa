# Quản lý thư viện — Trung tâm Y tế

Bản web tĩnh chạy trên GitHub Pages, thiết kế theo mẫu tham khảo.

## Cách tải lên GitHub
1. Tạo một repository mới trên GitHub (ví dụ `quan-ly-thu-vien`).
2. Tải `index.html` lên thư mục gốc repository.
3. Vào **Settings → Pages**.
4. Ở **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn branch `main`, folder `/ (root)`, rồi bấm **Save**.
6. Đợi GitHub Pages triển khai và mở URL được cung cấp.

## Chức năng
- Quản lý sách, nhập CSV, xuất danh mục CSV.
- Quản lý mượn/trả và lọc theo 9 nhà/khu.
- Danh sách truyện theo kỳ lưu trữ, nhập/xuất CSV.
- Báo cáo kèm ảnh minh chứng.
- Nhật ký thao tác, hồ sơ người đang thao tác.
- Xuất/nhập bản sao lưu JSON.

## Lưu ý quan trọng
Đây là ứng dụng frontend không có máy chủ. Dữ liệu lưu bằng `localStorage` trên trình duyệt đang sử dụng; không tự đồng bộ giữa thiết bị hoặc người dùng, không gửi email và không xác thực danh tính. Không nhập dữ liệu bệnh nhân hoặc thông tin nhạy cảm. Hãy xuất JSON định kỳ để sao lưu.
