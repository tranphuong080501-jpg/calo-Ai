CALORIE AI LITE - BẢN SỬA TỰ ZOOM VÀ CACHE

1. Sao lưu hai file index.html và sw.js hiện tại trên GitHub.
2. Thay cả hai file bằng index.html và sw.js trong gói này (đúng thư mục đang chạy ứng dụng).
3. Commit changes và đợi GitHub Pages deploy xong.
4. Trên iPhone, đóng hẳn Safari và ứng dụng web, sau đó mở lại khi có mạng.

Nếu vẫn tự zoom, kiểm tra Safari > aA > Website Settings > Page Zoom = 100%.

Lưu ý: Không xóa dữ liệu trang web/Safari vì nhật ký calo đang lưu trong localStorage.
Bản sw.js đổi cache v1 sang v2, xóa cache cũ và ưu tiên tải HTML mới từ mạng.
CSS đặt cỡ chữ input/select/textarea là 16px để ngăn Safari tự zoom khi focus.
