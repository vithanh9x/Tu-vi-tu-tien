# Tử Vi Lạc Hồng – Android APK

## Tính năng bản 1.1
- Cân Xương Tính Số dùng đủ bốn bảng: 60 hoa giáp, 12 tháng, 30 ngày, 12 giờ; đối chiếu 51 mức từ 2 lượng 1 chỉ đến 7 lượng 1 chỉ.
- Trợ lý luận giải nội bộ chạy bằng bộ quy tắc/tri thức tích hợp, không gọi Gemini/OpenAI và không cần API Key.
- Luận giải cung có xét vị trí thực tế của sao, trạng thái sáng/tối, sao đồng cung, tam hợp và xung chiếu.
- Icon ứng dụng mới phong cách Thiên Cung vàng trên nền thiên hà.

> Lưu ý: đây là bộ máy luận giải chuyên biệt theo quy tắc được đóng gói sẵn, không phải mô hình ngôn ngữ tổng quát như ChatGPT chạy cục bộ. Các thư viện giao diện/font hiện vẫn được tham chiếu từ CDN; muốn ứng dụng hiển thị đầy đủ khi hoàn toàn không có Internet cần đóng gói các thư viện đó vào assets ở một bước riêng.

## Build APK bằng GitHub Actions
1. Tải toàn bộ dự án lên một repository GitHub.
2. Mở tab **Actions** và chạy workflow **Build Android APK** (hoặc push lên nhánh `main`).
3. Tải artifact **TuViTienCanh-Android-APK**; bên trong có `app-debug.apk`.

## Build bằng Android Studio
Mở thư mục dự án, chờ Gradle sync, chọn **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
