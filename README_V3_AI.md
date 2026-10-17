# DENBROWN AI PHOTO FREE V3 — Face Detection

- Giữ nguyên tính năng ghép ảnh V2.
- Nút **AI · Nhận diện khuôn mặt**: tải MediaPipe Face Detector từ CDN, nhận diện ngay trên máy, không gửi ảnh lên máy chủ của ứng dụng.
- Kết quả số khuôn mặt hiện trên từng ảnh. Khi tạo trang, vùng crop ưu tiên tâm khuôn mặt (nếu nhận diện được).
- Cần Internet khi tải mô hình; mạng hoặc trình duyệt chặn CDN sẽ khiến AI không hoạt động, nhưng ghép ảnh thủ công vẫn dùng được.
- AI hiện chỉ phát hiện khuôn mặt, **không** xác định danh tính, cảm xúc, nghi lễ hoặc chất lượng ảnh. Với nhiều khuôn mặt nằm xa nhau, một số khuôn mặt vẫn có thể bị cắt bởi tỷ lệ ô ảnh.
- Cập nhật: giải nén, thay `index.html` trên nhánh `main` GitHub; Vercel tự triển khai lại nếu đã liên kết.
