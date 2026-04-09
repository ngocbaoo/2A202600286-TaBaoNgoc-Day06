# Individual reflection — Nguyễn Văn A (AI20K001)

## 1. Role
UI designer + developer + backend API. Phụ trách thiết kế giao diện người dùng, 
viết code cho giao diện người dùng và backend API.

## 2. Đóng góp cụ thể
- Thiết kế giao diện người dùng cho chatbot
- Viết code cho giao diện người dùng
- Viết code cho backend API

## 3. SPEC mạnh/yếu
- Mạnh nhất: Xác định bài toán thực tế: Tập trung đúng vào "nỗi đau" của dược sĩ là tra cứu thủ công mất thời gian (3-10 phút) và dễ sót cảnh báo. Định vị được AI chỉ là trợ lý, dược sĩ sẽ là người quyết định cuối cùng
- Yếu nhất: Dự án mới tập trung vào "thuốc thay thế" cùng hoạt chất, chưa xử lý sâu các trường hợp thay thế "tương đương trị liệu" (thay thế thuốc khác hoạt chất nhưng cùng nhóm điều trị).

## 4. Đóng góp khác
- Tìm kiếm được openFDA là một API cung cấp dữ liệu về thuốc là dữ liệu thuộc chính phủ nên không lo về uy tín
- Biên dịch và chuyển đổi các thuật ngữ y khoa phức tạp từ tiếng Anh sang tiếng Việt

## 5. Điều học được
- Cách thiết kế UI dễ nhìn, dễ sử dụng.
- Trong y tế, AI không được phép "đoán" liều lượng. Học được cách thiết lập các guardrails để AI chỉ đưa ra thông tin có bằng chứng từ FDA.
- Nếu như AI sai hoặc không chắc thì phải trả về là không biết hoặc không chắc chắn, không được đoán mò.

## 6. Nếu làm lại
Sẽ chốt được idea sớm hơn để chia việc cho mọi người trong D5. Qua D6 chỉ việc tập trung làm và không cần brainstorm lại quá nhiều, sẽ có nhiều thời gian hơn để suy nghĩ cho metric, eval, làm được UI chỉn chu hơn, fix các bug 429 và 503 trên gemini.

## 7. AI giúp gì / AI sai gì
- **Giúp:** dùng Gemini 2.5 flash để tổng hợp lại thông tin từ OpenFDA và từ database nội bộ để tim được các thuốc còn hàng mà có cùng hoạt chất, cùng nhóm điều trị với thuốc bị hết hàng.
- **Sai/mislead:** AI có gợi ý kê đơn thuốc nhưng hơi lạc đề so với scope ban đầu của nhóm là hỗ trợ dược sĩ gợi ý thuốc.
  Bài học: AI brainstorm tốt nhưng không biết giới hạn scope.