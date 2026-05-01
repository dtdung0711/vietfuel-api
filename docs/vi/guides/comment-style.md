# Quy ước comment trong code

Tài liệu này quy định cách viết comment thống nhất trong toàn bộ source.

## 1. Ngôn ngữ

- Sử dụng tiếng Việt có dấu cho tất cả comment mới.
- Tránh trộn tiếng Anh trong comment nếu không cần thiết.

## 2. Format

Ưu tiên một trong hai định dạng sau:

- Dòng đơn:
  - `// [MỤC] Nội dung ngắn gọn.`
- Khối logic:
  - `/* ==========================================================================`
  - ` * [MỤC] Mô tả ngắn.`
  - ` * ========================================================================== */`

## 3. Khi nào cần comment

Nên comment khi:

- Có fallback, retry, anti-bot, mapping nghiệp vụ.
- Có lý do kỹ thuật không hiển nhiên.
- Có ràng buộc dữ liệu để tránh bug ngầm.

Không cần comment khi:

- Code đã rõ nghĩa và tên biến/hàm đã tự mô tả.

## 4. Ví dụ

Đúng:

- `// [PVOIL] Nguồn trực tiếp bị chặn, chuyển sang fallback trung gian.`

Không đúng:

- `// get data`
- `// process`

## 5. Lộ trình chuyển đổi

Do dự án đã có lịch sử dài, việc chuyển đổi comment cũ sẽ thực hiện theo từng phần khi có sửa code.
Tất cả file mới và phần code mới bắt buộc tuân thủ quy ước này.
