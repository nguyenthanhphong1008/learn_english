# ENGLISH MASTER

Website học tiếng Anh chạy trực tiếp trên trình duyệt, sử dụng HTML, CSS và JavaScript thuần.

## Tính năng
- Trang tổng quan và thống kê học tập.
- Từ điển: tra từ tiếng Anh bằng Free Dictionary API (`dictionaryapi.dev`).
- Hiển thị phiên âm, loại từ, định nghĩa tiếng Anh và ví dụ khi API có dữ liệu.
- Danh sách từ mẫu có nghĩa tiếng Việt, ví dụ và cấp độ A1-C2.
- Flashcard, lọc cấp độ, phát âm bằng Speech Synthesis.
- Bài kiểm tra 10 câu hỏi ngẫu nhiên.
- Lưu từ yêu thích, từ đã học, điểm kiểm tra bằng localStorage.

## Cách chạy trên Visual Studio Code
1. Giải nén `ENGLISH_MASTER.zip`.
2. Mở Visual Studio Code.
3. Chọn **File > Open Folder...** và mở thư mục `english_master`.
4. Cài tiện ích **Live Server** trong Extensions (nếu chưa có).
5. Nhấp chuột phải vào `index.html` > **Open with Live Server**.
6. Website sẽ mở trong trình duyệt.

Bạn cũng có thể mở trực tiếp `index.html`, nhưng Live Server được khuyến nghị.

## Dữ liệu và giới hạn
- Website có bộ từ mẫu tiếng Anh–Việt được biên soạn sẵn để minh họa và học thử. Đây chưa phải kho từ vựng đầy đủ của Oxford hoặc toàn bộ từ tiếng Anh.
- Tra cứu mở rộng dùng Free Dictionary API tại `https://api.dictionaryapi.dev/`. Cần Internet; API chủ yếu cung cấp dữ liệu tiếng Anh như phiên âm, định nghĩa và ví dụ, không bảo đảm có bản dịch tiếng Việt.
- Phát âm sử dụng giọng đọc có sẵn trên thiết bị/trình duyệt. Giọng Anh-Anh được yêu cầu mặc định; giọng thực tế tùy hệ điều hành.
- Dữ liệu cá nhân của website được lưu trong trình duyệt hiện tại bằng localStorage, không đồng bộ giữa các thiết bị.

## Cấu trúc thư mục
```
english_master/
├── index.html
├── style.css
├── script.js
└── README.md
```
