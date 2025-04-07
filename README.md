# DragonBoyOnline-J2ME
![DragonBoy Logo](https://images.spiderum.com/sp-images/f9aabbc0449311ec885eab61bad4d8bd.png)
## 📱 Tổng quan
Chào mừng đến với DragonBoy Online J2ME Client, một phiên bản hiện đại hóa của tựa game MMORPG di động cổ điển Việt Nam ban đầu được phát triển cho các thiết bị Java ME (J2ME). Dự án này nhằm bảo tồn sự hoài niệm của trò chơi gốc và tối ưu hóa cho các thiết bị hỗ trợ công nghệ J2ME, với một số cải tiến giới hạn dựa trên khả năng của nền tảng.

## ✨ Tính năng
- **Tương thích giới hạn**: Chạy trò chơi trên một số thiết bị và nền tảng cụ thể hỗ trợ công nghệ J2ME
- **Đồ họa nâng cao**: Cải thiện hiển thị sprite và hiệu ứng hình ảnh trong khi vẫn giữ phong cách pixel art quyến rũ
- **Tối ưu hóa mạng**: Giảm độ trễ và cải thiện độ ổn định kết nối
- **Giao diện hiện đại**: Thiết kế lại giao diện để dễ sử dụng hơn trong khi vẫn giữ cảm giác cổ điển
- **Gameplay mở rộng**: Bổ sung nhiệm vụ, vật phẩm và tùy chọn tùy chỉnh nhân vật
- **Lưu trạng thái**: Đồng bộ hóa đám mây cho tiến trình trò chơi

## 🚀 Bắt đầu
### Yêu cầu hệ thống
- Thiết bị hỗ trợ J2ME (Java ME)
- Java Runtime Environment cho thiết bị tương thích
- Tối thiểu 64MB RAM (tùy theo thiết bị)

### Cài đặt
#### Máy tính
```bash
git clone https://github.com/duykhongphai/DragonBoyOnline-J2ME.git
cd DragonBoyOnline-J2ME
./gradlew build
```

## 🛠️ Phát triển
Dự án này sử dụng một lớp giả lập J2ME tùy chỉnh để chạy mã trò chơi gốc với các cải tiến hiện đại.

### Xây dựng từ mã nguồn
```bash
# Cài đặt các gói phụ thuộc
./gradlew dependencies
# Xây dựng cho tất cả các nền tảng
./gradlew buildAll
```

### Kiến trúc
Client tuân theo kiến trúc phân lớp:
- Lớp giả lập J2ME cốt lõi
- Module giao tiếp mạng
- Hệ thống xử lý đầu vào
- Quản lý tài nguyên

## 📝 Giấy phép
Dự án này được cấp phép theo Giấy phép MIT - xem tệp [LICENSE](LICENSE) để biết chi tiết.

## 🙏 Lời cảm ơn
- Các nhà phát triển game DragonBoy gốc
- Cộng đồng bảo tồn J2ME
- Tất cả những người đóng góp đã giúp dự án này trở thành hiện thực

## 📞 Liên hệ
- Vấn đề: [GitHub Issues](https://github.com/duykhongphai/DragonBoyOnline-J2ME/issues)

---
⭐ **Hãy gắn sao cho repository này nếu bạn thấy nó hữu ích!** ⭐
