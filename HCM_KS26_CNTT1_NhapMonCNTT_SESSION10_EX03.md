# HCM_KS26_CNTT1_NhapMonCNTT_SESSION010_03
## Phần 1. Phân tích bài toán:
- Lý do Markdown lại giúp AI xử lý nhanh hơn dựa trên cơ chế chia nhỏ Token: HTML dùng cặp thẻ mở và đóng cho mỗi định dạng, còn Markdown chỉ dùng một hai ký tự. Khi đếm cùng một nội dung "chữ"

## Phần 2. So sánh & Đánh giá:
### Bảng so sánh Markdown và HTML
| Tiêu chí | Markdown | HTML |
|---|---|---|
| Số ký tự cho cùng định dạng|Rất ít  | Nhiều |
|Tiêu thụ token | Thấp | Cao |
| Tốc độ xử lý của AI | Chuỗi ngắn nên nhanh hơn | Chuỗi dài hơn nên thường chậm hơn |
| Dễ sửa lỗi | Sai 1 ký tự chỉ lệch đúng chỗ đó | Thiếu một thẻ đóng có thể làm vỡ cả khối giao diện |
| Quen thuộc với AI | AI trả lời mặc định bằng Markdown | AI hiểu tốt nhưng thường không phải định dạng mặc định |
### Giải pháp tối ưu cho hệ thống "GreenTech":
- Chọn Markdown làm định dạng chính giữa hệ thống và AI, và chuyển sang HTML ở lớp hiển thị.
### Lập luận
- Chi phí: hệ thống trả lời hàng nghìn câu hỏi mỗi ngày, nên chênh lệch token nhỏ ở mỗi lượt nhân lên thành khoản tiết kiệm đáng kể.
- Tốc độ: nông dân cần câu trả lời nhanh trên điện thoại, đôi khi mạng yếu. Chuỗi ngắn hơn giúp phản hồi gọn hơn.
- Người vận hành: đội kỹ thuật và chuyên gia nông nghiệp có thể đọc, sửa tri thức trực tiếp trong file .md mà không cần biết HTML. Dữ liệu thô vẫn đọc được ngay cả khi lỗi.
- Khả năng mở rộng: Markdown tương thích với Git (xem lịch sử sửa nội dung) và có thể chuyển sang HTML bất cứ lúc nào, trong khi chiều ngược lại khó hơn.# HCM_KS26_CNTT1_NhapMonCNTT_SESSION10_03

