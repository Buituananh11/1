# Chạy thử (KHÔNG mở index.html bằng double-click — sẽ trắng màn hình)
Windows: bấm đúp `start.bat` (cần Python hoặc Node).
Hoặc trong thư mục này chạy:  python -m http.server 8000   /   npx serve .
Rồi mở http://localhost:8000

# Ảnh rơi
- Thêm ảnh vào `images/`, sửa `FALL_IMAGES` gần cuối `static/js/home.js`.
- `FALL_COUNT` số ảnh (hiện 70), `FALL_BRIGHT` độ sáng (0.3–1; nhỏ = tối hơn), `FALL_SIZE` kích thước.
