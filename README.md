# BÁO CÁO PHÂN TÍCH VÀ SỬA LỖI QUY TRÌNH PLANNING POKER CHO DỰ ÁN RIKKEIGO

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Nhiệm vụ 1: Phân tích lỗi sai trong buổi Planning Poker

Dưới đây là bảng phân tích chi tiết các PBI dựa trên quy tắc Planning Poker và các nguyên tắc Agile/Scrum đã học.

| Mã | Hợp lý / Chưa hợp lý | Quy tắc bị vi phạm | Hậu quả khi lập kế hoạch Sprint |
| --- | --- | --- | --- |
| P1 | Chưa hợp lý | Lấy trung bình cộng các con số | Ước lượng không phản ánh đúng độ phức tạp thực tế, làm sai lệch Velocity của đội. |
| P2 | Chưa hợp lý | Product Owner quyết định SP | Vi phạm quyền tự chủ của Developers, gây áp lực sai lệch về tiến độ. |
| P3 | Hợp lý | Không vi phạm | Đội đã thực hiện đúng quy trình thảo luận và chốt lại trên thang Fibonacci. |
| P4 | Chưa hợp lý | Quy đổi SP sang giờ | Vi phạm nguyên tắc SP là độ lớn tương đối, gây hiểu lầm về năng suất và khó quản lý rủi ro. |
| P5 | Chưa hợp lý | Chốt theo đa số khi chưa rõ yêu cầu | Bỏ qua rủi ro tiềm ẩn, dẫn đến nợ kỹ thuật hoặc vỡ kế hoạch Sprint. |

## Nhiệm vụ 2: Đề xuất cách xử lý cho các PBI chưa hợp lý

Dưới đây là phương án xử lý cho từng PBI để đảm bảo tính minh bạch và chính xác cho các Sprint tiếp theo:

- P1 (Đăng nhập): Đội cần thảo luận lại về các rủi ro tích hợp (như xác thực OTP, bảo mật). Sau khi làm rõ, mỗi thành viên chọn lại thẻ trên thang Fibonacci, không lấy trung bình.
- P2 (Thanh toán): Product Owner cần giải thích rõ giá trị nghiệp vụ, sau đó để Developers tự ước lượng dựa trên độ phức tạp kỹ thuật. Tuyệt đối không ép con số để kịp kế hoạch.
- P4 (Vị trí tài xế): Cần loại bỏ ghi chú quy đổi sang giờ. Đội nên tập trung thảo luận về độ khó của việc tích hợp API bản đồ và chốt lại SP dựa trên sự đồng thuận.
- P5 (Mã giới thiệu): Đây là PBI chưa rõ ràng. Đội cần dừng lại, yêu cầu Product Owner làm rõ quy tắc áp dụng khuyến mãi trước khi tiến hành ước lượng lại.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
