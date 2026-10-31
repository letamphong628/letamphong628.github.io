# Chính Sách Bảo Mật (Security Policy)

## Các Phiên Bản Được Hỗ Trợ (Supported Versions)

EduZone hiện đang được phát triển và duy trì liên tục trên GitHub Pages. Chúng tôi ưu tiên hỗ trợ các bản cập nhật bảo mật cho phiên bản mới nhất đang hoạt động.

| Phiên Bản (Version) | Trạng Thái Hỗ Trợ (Supported) | Ghi Chú |
| ------------------- | ----------------------------- | ------- |
| 2.0.x (Hiện tại)    | :white_check_mark:            | Bản có Đấu Trường PvP 1v1 & tích hợp Gemini AI |
| 1.x.x               | :x:                           | Bản thử nghiệm cũ (Không còn hỗ trợ) |

---

## Báo Cáo Lỗ Hổng Bảo Mật (Reporting a Vulnerability)

Chúng tôi luôn coi trọng tính an toàn, bảo mật dữ liệu và trải nghiệm công bằng cho toàn thể học sinh sử dụng nền tảng EduZone.

Nếu bạn phát hiện bất kỳ sự cố hoặc lỗ hổng bảo mật nào (như lộ khóa API, rò rỉ dữ liệu Firebase Realtime Database, gian lận điểm số hoặc tấn công giao diện):

### 1. Cách Thức Gửi Báo Cáo
* **Vui lòng KHÔNG mở Public Issue** trên kho lưu trữ (để tránh kẻ xấu lợi dụng trước khi lỗi được khắc phục).
* Gửi thông tin trực tiếp qua mục “Góp Ý” của Website

### 2. Thông Tin Cần Cung Cấp
Để giúp quá trình xác minh diễn ra nhanh chóng, vui lòng đính kèm:
* Mô tả chi tiết về lỗ hổng (XSS, lỗ hổng phân quyền, rò rỉ khóa xác thực, lỗi logic phòng đấu...).
* Các bước tái hiện lỗi (Proof of Concept - PoC) hoặc ảnh chụp màn hình minh họa.
* Mức độ ảnh hưởng ước tính đối với người dùng hoặc hệ thống.

### 3. Quy Trình Xử Lý
* **Phản hồi xác nhận:** Chúng tôi sẽ phản hồi lại email của bạn trong vòng **24 - 48 giờ** kể từ khi nhận được báo cáo.
* **Đánh giá & Khắc phục:** Nếu lỗi được xác nhận, chúng tôi sẽ tiến hành vá mã nguồn, thu hồi các thông tin đăng nhập bị lộ hoặc cập nhật quy tắc bảo mật Firebase trong vòng **3 - 5 ngày**.
* **Công bố:** Sau khi lỗ hổng đã được khắc phục hoàn toàn trên bản chạy thực tế (`letamphong628.github.io`), thông tin sẽ được cập nhật công khai và ghi nhận đóng góp của bạn.
