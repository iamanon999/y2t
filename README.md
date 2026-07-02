# Y2T (YouTube To TikTok) 🚀

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)

**Y2T** là bộ công cụ tự động hóa toàn diện giúp bạn theo dõi kênh YouTube, tải video, tự động render và đăng tải (Upload) lên nền tảng TikTok một cách hoàn toàn tự động. Hệ thống bao gồm giao diện điều khiển hiện đại và một Daemon chạy ngầm cực kỳ mạnh mẽ.

---

## 🌟 Tính năng Nổi bật

- **Tự động theo dõi (Auto Tracking):** Phát hiện video mới nhất từ danh sách kênh YouTube bạn đã đăng ký.
- **Tải Video Đa dạng:** Hỗ trợ tải bằng `ytdlp` hoặc API nội bộ (`apidl`), với đầy đủ tùy chọn độ phân giải (1080p, 720p...) và lọc loại video (Shorts, Long, hoặc Cả hai).
- **Auto Render:** Xử lý và đóng dấu video sau khi tải để phù hợp với định dạng của TikTok.
- **Auto Upload:** Tự động đăng video lên TikTok bằng nhiều tài khoản cùng lúc. Hỗ trợ kèm Proxy và Hashtag riêng cho từng kênh.
- **Quản lý Cookies Thông minh:** Hỗ trợ lưu trữ Cookies để lách chống bot và bảo mật tài khoản.
- **Giao diện Dashboard Tương tác:** Giao diện Fyne trực quan, cho phép Sort dữ liệu một chạm, Select All / Deselect All nhanh chóng, có cả Light Mode & Dark Mode.


---

## 📥 Cài đặt & Cấu hình

### 1. Tải về và Giải nén
Tải file Release mới nhất tại mục [Releases](https://github.com/iamanon999/Y2T/releases). Sau khi giải nén, bạn sẽ thấy cấu trúc như sau:
```
Y2T/
├── y2t.exe      # Giao diện điều khiển (Chạy file này)
├── bin/                     # Chứa ffmpeg, ffprobe, và Daemon
│   ├── ytdlp_daemon.exe
│   ├── ffmpeg.exe
│   └── ...
└── data/                    # Nơi lưu trữ cấu hình & Cookies (Tự sinh)
```

## 💻 Hướng dẫn Sử dụng

### 1. Đăng nhập hệ thống
- Mở `y2t.exe`.
- Điền tài khoản và mật khẩu được cung cấp. Nếu đăng nhập thành công, cửa sổ Dashboard sẽ xuất hiện chính giữa màn hình.

### 2. Tab Dashboard (Bảng Điều khiển Trung tâm)
Đây là nơi bạn quản lý toàn bộ các kênh YouTube cần theo dõi:
- **Thêm kênh:** Dán URL kênh YouTube vào ô trống và nhấn Enter.
- **Click vào các Tiêu đề Cột (Header):**
  - **No, Name, Video ID, Date, Detected:** Click để sắp xếp (Sort) dữ liệu từ A-Z hoặc ngược lại.
  - **Download, Render, Upload:** Click vào chữ trên tiêu đề để Tích chọn/Bỏ chọn toàn bộ (Select All) các kênh bên dưới.
  - **Account:** Click vào chữ "Account" để mở nhanh thư mục chứa file Cookies `data/cookies` thông qua Windows Explorer.
- **Chỉnh sửa Cấu hình Từng Kênh:** Bạn có thể chọn tải Shorts/Long, thêm Hashtag, gán Proxy (`user:pass@ip:port`) hoặc đổi Account TikTok trực tiếp trên từng dòng.

### 3. Tab Logs (Nhật ký) & Notifications (Thông báo)
- **Logs:** Xem lịch sử tải, render, và tiến trình đăng video kèm theo cột "Total Time" (Tổng thời gian xử lý).
- **Notifications:** Bảng thông báo theo dõi sát sao tiến độ. Có thể nhấn trực tiếp vào link màu Cam (Channel) hoặc link màu Trắng (Video) để mở thẳng trên trình duyệt.

---

## 📝 Hỗ trợ

- Liên hệ **[iamanon999](https://github.com/iamanon999)**.
