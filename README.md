# 💖 Trang Web Chúc Mừng Ngày Phụ Nữ Việt Nam 20/10

Một trang web tương tác lãng mạn, hiện đại dành tặng người yêu/bạn gái nhân ngày Phụ nữ Việt Nam (20/10). Trang web kết hợp hiệu ứng hình ảnh động, hiệu ứng ánh sáng (glowing/neon), nhạc nền, chữ gõ tự động và giao diện phát nhạc kèm lời bài hát.

---

## ✨ Tính năng nổi bật

- **Giao diện Night-Drive & Neon:** Sử dụng tông màu tím, hồng pastel và xanh cyan glowing tạo cảm giác hiện đại, ngọt ngào và ấm áp.
- **Mắt Robot LED biểu cảm:** Đôi mắt robot xanh neon tự động nhấp nháy, nheo mắt hoặc biến thành hình trái tim đập theo nhịp.
- **Tương tác trái tim:** Trái tim trung tâm với hiệu ứng nhịp đập, bấm vào để mở các thông điệp.
- **Hiệu ứng chữ gõ tự động (Typing effect):**
  - Hiển thị các câu chúc/lời nhắn theo từng đoạn.
  - Hỗ trợ bấm/chạm vào khung chữ để tăng tốc độ gõ (đọc nhanh).
  - Thanh tiến trình (progress bar) hiển thị khoảng thời gian giữa các đoạn.
- **Nút bấm kích thước lớn (Big Sparkle Button):** Nút kêu gọi hành động với hiệu ứng chuyển màu rực rỡ và ánh sáng chạy qua.
- **Bảng lời chúc cuối (Final Panel):**
  - 4 thẻ lời chúc thiết kế tỉ mỉ với icon xinh xắn (`🌸`, `🍀`, `🎀`, `💫`).
  - Lời nhắn kết luận đầy tình cảm.
- **Trang phát nhạc & Lời bài hát (Lyrics/Music Player):**
  - Đĩa nhạc xoay tròn hiệu ứng vinyl.
  - Ảnh poster bài hát floating sinh động.
  - Thanh tiến trình phát nhạc và nút Play/Pause.
  - Bấm vào ảnh poster để phóng to xem chi tiết (Lightbox).
- **Âm thanh & Nhạc nền:**
  - Nhạc nền vòng lặp (BGM) phát nhẹ nhàng khi tương tác.
  - Nhạc bài hát chính phát riêng biệt ở phần Lyrics.
- **Hiệu ứng Canvas:** Hiệu ứng sao nhấp nháy và hoa rơi lung linh.
- **Tối ưu hóa thiết bị:** Đã hỗ trợ Safe Area cho iOS/Android và responsive hoàn hảo trên điện thoại di động.

---

## 🛠️ Công nghệ sử dụng

- **HTML5:** Cấu trúc semantic, hỗ trợ các thẻ Audio, Canvas và SVG.
- **CSS3:**
  - **Variables (`:root`):** Quản lý bảng màu thống nhất.
  - **Animations & Keyframes:** Tạo các hiệu ứng nhịp đập, nhấp nháy, chuyển động mượt mà.
  - **Flexbox & Grid:** Căn chỉnh layout linh hoạt.
  - **Backdrop Filter & Glassmorphism:** Hiệu ứng kính mờ cho các bảng tin.
  - **Google Fonts:** `Quicksand`, `Pacifico`, `Be Vietnam Pro`.
- **JavaScript (Vanilla JS):** Điều khiển luồng tương tác, hiệu ứng gõ chữ, Canvas particle, phát âm thanh và quản lý trạng thái giao diện.

---

## 📁 Cấu trúc thư mục

```text
 project/
 ├── index.html        # File HTML duy nhất chứa toàn bộ CSS, JS và tài nguyên nhúng
 └── README.md         # File hướng dẫn dự án
```

> **Lưu ý:** Tất cả mã nguồn CSS và JS đã được tích hợp gọn gàng trong file `index.html` để dễ dàng chia sẻ và triển khai nhanh.

---

## 🚀 Hướng dẫn sử dụng & Triển khai

### 1. Chạy trực tiếp trên máy cục bộ
1. Tải file `index.html` về máy tính.
2. Mở file bằng bất kỳ trình duyệt web nào (Chrome, Safari, Edge, Firefox).

### 2. Triển khai Online (Miễn phí)
Bạn có thể dễ dàng tải trang web này lên các nền tảng lưu trữ tĩnh miễn phí để gửi link cho người ấy:
- **GitHub Pages:** Tạo repository -> Tải `index.html` lên -> Bật GitHub Pages trong phần Settings.
- **Vercel / Netlify:** Kéo thả thư mục chứa file `index.html` vào giao diện deploy của Vercel hoặc Netlify.

---

## 🎵 Tài nguyên phương tiện (Media)

- **Nhạc nền 1 (BGM):** Lấy từ Host Catbox (`https://files.catbox.moe/kvi7zu.mp3`).
- **Nhạc bài hát chính:** *Cô Người Tình - Huy.G ft. LAG x Thuận* (`https://files.catbox.moe/vu0uws.mp3`).
- **Ảnh Poster:** Được mã hóa trực tiếp dưới dạng `Base64` bên trong HTML để giảm thiểu lỗi mất ảnh khi gửi file.

---

## 💌 Tùy chỉnh lời chúc (Customization)

Nếu muốn thay đổi lời chúc theo ý thích riêng:
1. Mở file `index.html` bằng một trình chỉnh sửa mã nguồn (VS Code, Notepad++, v.v.).
2. Tìm các dòng chứa thẻ `<div class="wish">` hoặc thẻ `<div class="sign">` để chỉnh sửa nội dung văn bản.
3. Thay đổi tiêu đề tại `<div class="title">` hoặc các đoạn văn bản trong script theo nhu cầu của bạn.

---

✈️ *Chúc bạn và người thương có một ngày 20/10 thật hạnh phúc và ý nghĩa!* 💖