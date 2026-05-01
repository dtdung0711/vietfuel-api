# Hướng dẫn đóng góp cho VietFuelAPI

Cảm ơn bạn đã quan tâm đóng góp cho VietFuelAPI.

## Nguyên tắc chung

- Dự án phi lợi nhuận, phục vụ học tập, nghiên cứu kỹ thuật và cộng đồng.
- Không đại diện cho bất kỳ tổ chức, doanh nghiệp hoặc cơ quan nhà nước nào.
- Tôn trọng nguồn dữ liệu công khai và giới hạn kỹ thuật của các website nguồn.

## Quy trình đóng góp

1. Fork repository và tạo branch mới từ `main`.
2. Đặt tên branch rõ ràng: `feat/...`, `fix/...`, `docs/...`, `refactor/...`.
3. Chạy test trước khi tạo Pull Request: `npm --prefix backend test`.
4. Mở Pull Request với mô tả đầy đủ: vấn đề, nguyên nhân, cách sửa, ảnh hưởng.

## Quy ước commit

- Sử dụng commit message bằng tiếng Anh, ngắn gọn và mô tả đúng thay đổi.
- Gợi ý format: `type(scope): short summary`.
- Ví dụ: `fix(pvoil): harden fallback parser against cloudflare-protected source`.

## Quy ước comment trong code

- Tất cả comment mới phải viết bằng tiếng Việt có dấu.
- Trình bày thống nhất theo mẫu: `// [MỤC] Nội dung ngắn gọn, rõ ràng.`
- Ưu tiên comment cho các phần: logic khó, fallback, rule nghiệp vụ, anti-bot, xử lý lỗi.
- Không comment lại điều mà code đã tự mô tả rõ.

Tham khảo thêm tại `docs/vi/guides/comment-style.md`.

## Quy ước code

- Không chèn thông tin nhạy cảm (token, cookie, credential) vào code.
- Không commit file runtime: logs, dump HTML, cache sinh động.
- Khi sửa scraper: ưu tiên giảm tải nguồn, thêm fallback an toàn, giữ metadata rõ ràng.

## Checklist Pull Request

- [ ] Đã chạy test backend và pass.
- [ ] Đã cập nhật tài liệu liên quan (nếu cần).
- [ ] Không có file debug/runtime không cần thiết.
- [ ] Tuân thủ quy ước comment tiếng Việt.
- [ ] Có mô tả ảnh hưởng pháp lý nếu thay đổi disclaimer/legal.

## Báo lỗi

Khi tạo issue, vui lòng cung cấp:

- Endpoint bị ảnh hưởng.
- Nguồn dữ liệu liên quan.
- Log lỗi (nếu có).
- Cách tái hiện.

Cảm ơn bạn đã giúp dự án ổn định hơn cho cộng đồng.
