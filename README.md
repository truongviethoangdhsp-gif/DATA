# DATA CTSV – UFLS | Bản DEMO giao diện + Excel

## Chạy ngay
1. Giải nén ZIP.
2. Mở `index.html` bằng Chrome hoặc Edge.
3. Không cần tài khoản, mật khẩu, Supabase hay cấu hình backend.
4. Vào từng danh mục và import file `.xlsx`, `.xls` hoặc `.csv`.

## Chức năng
- Dashboard tổng quan và biểu đồ cơ cấu dữ liệu.
- 3 danh mục mặc định: Học bổng, Tuyển dụng, Doanh nghiệp.
- Tạo danh mục mở rộng.
- Import Excel: xem trước, thêm mới, gộp (bỏ dòng trùng hoàn toàn), thay thế toàn bộ.
- Tìm kiếm toàn văn, lọc theo cột, phân trang, xuất Excel.
- Dữ liệu demo lưu trong `localStorage` của trình duyệt.

## Lưu ý quan trọng
Đây là bản xem giao diện và thử luồng Excel. Dữ liệu chỉ nằm trong trình duyệt/máy đang mở, không tự đồng bộ sang máy khác và có thể mất nếu xóa dữ liệu trình duyệt. Không dùng dữ liệu cá nhân/sinh viên thật ở giai đoạn này. Khi chốt giao diện và mẫu Excel, nâng cấp sang Supabase để nhiều người dùng chung dữ liệu.

## Thư viện ngoài
SheetJS và Chart.js được tải từ CDN, vì vậy cần kết nối Internet khi mở trang để import/export Excel và hiển thị biểu đồ.

## Footer
Footer hiển thị dòng “Design by ZrVietHoang” ở cuối khu vực nội dung. Chỉnh trong `index.html`, class `.site-footer`.
