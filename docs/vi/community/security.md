# Chính sách bảo mật

## Phiên bản được hỗ trợ

Hiện tại dự án chỉ hỗ trợ branch chính `main`.

## Báo cáo lỗ hổng bảo mật

Nếu bạn phát hiện lỗ hổng bảo mật:

1. Không công khai ngay lập tức trên issue công khai.
2. Tạo issue với nhãn `security` và mô tả tối thiểu thông tin khai thác.
3. Kèm hướng tái hiện và mức độ ảnh hưởng.

Maintainer sẽ phản hồi sớm nhất có thể và đưa ra hướng xử lý.

## Ghi chú bảo mật

- Dự án không thu thập thông tin nhận dạng người dùng.
- Không yêu cầu auth token cho endpoint công khai.
- Đã áp dụng các biện pháp cơ bản: `helmet`, `rate limiting`, `cache-control`.

## Phạm vi báo cáo

Ưu tiên báo cáo liên quan đến:

- RCE / command injection.
- SSRF.
- Header misconfiguration nghiêm trọng.
- Lộ thông tin nhạy cảm.
