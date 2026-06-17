Cấu trúc gợi ý cho các bài tập web (tập luyện)

- Mỗi bài tập đặt trong một thư mục riêng, ví dụ `HomeWork1`, `HomeWork2`, ...
  - Mỗi thư mục chứa ít nhất: `index.html`, `styles.css`, và thư mục `assets/` nếu cần ảnh.
  - `index.html` trong thư mục bài tập nên dùng đường dẫn tương đối tới `styles.css` và `assets/` trong cùng thư mục.

Ví dụ:

New folder/
├─ HomeWork5/
│  ├─ index.html
│  ├─ styles.css
│  └─ Asset/giày.webp
├─ index.html  <- trang chỉ mục (liệt kê các bài tập)
└─ README.md

Hướng dẫn nhanh để thêm bài tập mới:
1. Tạo thư mục `HomeWorkN`.
2. Thêm `index.html` và `styles.css` vào thư mục đó.
3. Nếu có ảnh, tạo thư mục `Asset` (hoặc `assets`) trong cùng thư mục và tham chiếu tương đối.
4. Mở `index.html` ở thư mục gốc để truy cập nhanh các bài tập.

Lưu ý:
- Sử dụng đường dẫn tương đối (không dùng tuyệt đối) để dễ di chuyển hoặc deploy.
- Tên tệp phải là `index.html` để có thể mở thư mục trực tiếp trong trình duyệt.
