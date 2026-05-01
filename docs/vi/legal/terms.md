# Điều khoản sử dụng — VietFuelAPI

> Cập nhật lần cuối: 26 tháng 4, 2026

---

## 1. Chấp thuận điều khoản

Bằng cách truy cập trang web này hoặc sử dụng dữ liệu từ **VietFuelAPI**, bạn đồng ý tuân thủ toàn bộ các điều khoản dưới đây. Nếu không đồng ý, vui lòng ngừng sử dụng ngay lập tức.

---

## 2. Giấy phép mã nguồn

Mã nguồn của VietFuelAPI được phát hành theo giấy phép **MIT**:

- Được phép sử dụng, sao chép, sửa đổi và phân phối lại cho **mọi mục đích**, kể cả thương mại.
- Yêu cầu duy nhất: giữ lại thông báo bản quyền gốc.
- Xem chi tiết tại: [`LICENSE`](../../../LICENSE) trong thư mục gốc dự án.

Tuy nhiên, **dữ liệu được thu thập** (giá xăng dầu từ các nguồn bên ngoài) không thuộc quyền sở hữu của VietFuelAPI và chịu điều khoản riêng của từng nguồn.

---

## 3. Quyền sở hữu trí tuệ

Tất cả tên thương mại, logo và nhãn hiệu từ các nguồn dữ liệu tích hợp (Petrolimex, PVOil, Mipec, COMECO, Saigon Petro, Petro Times, WebGia, GiaXangHomNay…) là **tài sản của đơn vị quản lý tương ứng**. Chúng chỉ xuất hiện trong dự án để nhận diện nguồn dữ liệu.

---

## 4. Giới hạn sử dụng & Bảo vệ hệ thống

Để bảo vệ hạ tầng cộng đồng, các hành vi sau bị **nghiêm cấm**:

| Hành vi | Giải thích |
|:---|:---|
| Tấn công DDoS | Gây quá tải server cố ý |
| Vượt rate limit | >60 req/phút (quốc gia) hoặc >20 req/phút (tỉnh thành) mỗi IP |
| Dùng dữ liệu lừa đảo | Trình bày dữ liệu sai lệch có chủ đích để lừa đảo người dùng |
| Reverse-engineering | Cố ý bypass các biện pháp bảo vệ để khai thác hệ thống |
| Resell dữ liệu | Bán lại dữ liệu API như sản phẩm thương mại mà không có attribution |

Vi phạm có thể dẫn đến **khóa IP vĩnh viễn** và thông báo đến nhà cung cấp dịch vụ.

---

## 5. Trách nhiệm người tích hợp

Nếu bạn tích hợp VietFuelAPI vào ứng dụng hoặc dịch vụ của mình:

- **Attribution bắt buộc**: Ghi rõ nguồn `VietFuelAPI` hoặc link đến dự án.
- **Thông báo Disclaimer**: Phổ biến rõ cho người dùng cuối rằng dữ liệu chỉ mang tính tham khảo.
- **Không thay thế giá chính thức**: Không trình bày dữ liệu là nguồn chính thức từ Bộ Công Thương hay các công ty xăng dầu.

---

## 6. Điều khoản hành vi Bot & Scraping

VietFuelAPI hoạt động như một bot thu thập dữ liệu công khai. Chúng tôi cam kết:

- Sử dụng **User-Agent minh bạch** (`VietFuelBot/1.0`) để nguồn nhận diện được.
- Tuân thủ **robots.txt** của các nguồn dữ liệu khi có.
- Không lưu trữ dữ liệu nhạy cảm hoặc thông tin cá nhân.
- Dừng thu thập ngay khi nhận được yêu cầu hợp lệ từ chủ sở hữu nguồn.

---

## 7. Miễn trừ bảo hành dịch vụ

VietFuelAPI được cung cấp theo nguyên tắc **"nguyên trạng" (as-is)**. Chúng tôi không đảm bảo:

- Tính liên tục của dịch vụ 24/7.
- Dữ liệu luôn phản ánh giá thực tế ngay lập tức.
- Khả năng hoạt động khi nguồn gốc thay đổi cấu trúc hoặc triển khai chặn truy cập.

Trong các tình huống trên, API sẽ trả về dữ liệu cache cũ kèm cờ `"isStale": true`.

---

## 8. Thay đổi điều khoản

VietFuelAPI có quyền cập nhật điều khoản này bất cứ lúc nào. Ngày "Cập nhật lần cuối" ở đầu tài liệu sẽ phản ánh thay đổi mới nhất. Việc tiếp tục sử dụng API sau khi có thay đổi được coi là chấp nhận điều khoản cập nhật.

---

🔗 [Trở về chỉ mục pháp lý](README.md) | [English →](../../en/legal/terms.md)