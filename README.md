# Calorie AI Lite – miễn phí

Phiên bản PWA tĩnh, không cần backend, API key hay tài khoản. Chạy trên trình duyệt và lưu nhật ký bằng localStorage trên thiết bị.

## Dùng thử
Mở `public/index.html` trên trình duyệt để thử các chức năng cơ bản. Để cài PWA lên iPhone và hỗ trợ offline, đưa nội dung thư mục `public` lên hosting HTTPS (có thể dùng GitHub Pages miễn phí), sau đó mở bằng Safari → Chia sẻ → Thêm vào màn hình chính.

## Có gì?
- Nhật ký bữa ăn theo gram, kcal, protein, carb, fat.
- Món ăn phổ biến và công thức quy đổi khẩu phần.
- Tính BMR/TDEE, mục tiêu giảm cân mặc định TDEE - 300 kcal.
- Theo dõi lịch sử 7 ngày và cân nặng.
- Xuất dữ liệu JSON.
- Tra cứu Calo bằng ChatGPT miễn phí bên ngoài app, sau đó nhập số liệu thủ công.

## Lưu ý
- Không gọi OpenAI API, không có chi phí API.
- Dữ liệu chỉ lưu trên trình duyệt hiện tại. Hãy xuất JSON sao lưu; xóa dữ liệu trình duyệt có thể làm mất nhật ký.
- ChatGPT miễn phí có giới hạn sử dụng riêng và kết quả dinh dưỡng là ước tính.
- Không có đồng bộ nhiều thiết bị hoặc nhận diện ảnh tự động.
