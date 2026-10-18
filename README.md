# Book Landing Page - Trang Giới Thiệu Sách (Responsive Bootstrap)

Dự án trang web tĩnh giới thiệu về sách chuyên nghiệp, được xây dựng và responsive hoàn chỉnh dựa trên mẫu thiết kế từ repository tham khảo: [hoanv7169/bootstrap-demo](https://github.com/hoanv7169/bootstrap-demo).

---

## Các thành phần cấu trúc của trang
Trang web bao gồm đầy đủ 8 phần theo đúng yêu cầu đề bài:
1. **Header & Book Overview**: Thanh điều hướng Navbar với thương hiệu `Books`, giỏ hàng/menu liên kết và Hero Section giới thiệu cuốn sách "Exciting Adventure" cùng nút CTA "Buy now for $5.99".
2. **Author Section**: Giới thiệu về tác giả nổi bật (*Mr. Devid Smith*), chân dung tác giả và tiểu sử sáng tác.
3. **Features**: Những tính năng và điểm đặc biệt làm nên sự độc đáo của cuốn sách, kết hợp khối số liệu ấn tượng (Happy Clients, Tickets Submitted, Total Projects).
4. **Prices (Bảng giá)**: 3 gói mua sách linh hoạt: **PDF**, **E-book**, **Paperback** với mức giá rõ ràng và nút đặt mua ngay.
5. **Download**: Khối tải ứng dụng đọc sách đa nền tảng (**Desktop** trên website & **Mobile** trên Google Play / App Store).
6. **Reader’s Say**: Phần đánh giá và cảm nhận của độc giả có tích hợp Bootstrap Carousel trình chiếu các nhận xét chân thực từ CEO & chuyên gia.
7. **Footer**: Thông tin About Us, biểu mẫu đăng ký nhận bản tin Newsletter và các icon mạng xã hội liên kết.
8. **Responsive**: Đảm bảo hiển thị tối ưu trên mọi độ phân giải màn hình từ Desktop, Tablet cho đến các thiết bị di động (Mobile).

---

## Cấu trúc thư mục dự án
```text
book-landing-page/
├── index.html       ← Trang chủ giới thiệu sách với đầy đủ các phần
├── assets/          ← Thư mục hình ảnh đầy đủ của dự án
│   ├── header-img.png
│   ├── pexels-photo-1904769.jpeg (Ảnh tác giả)
│   ├── pexels-photo-179941.jpeg
│   ├── UI-face-1.jpg
│   ├── UI-face-2.jpg
│   ├── UI-face-3.jpg
│   ├── UI-face-4.jpg
│   └── ...
├── css/
│   ├── style.css    ← Định kiểu giao diện phong cách gradient, typography nghệ thuật
│   └── mobile.css   ← Tối ưu responsive trên màn hình nhỏ và di động
├── js/
│   └── main.js      ← Script xử lý tương tác navbar sticky và sự kiện cuộn
└── README.md
```

---

## Cách chạy dự án
Mở trực tiếp tệp `index.html` trong bất kỳ trình duyệt web nào (Chrome, Edge, Firefox, Safari,...).
