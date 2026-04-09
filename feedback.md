# Feedback - Demo round Day 6

## Bàn B5: 
|Tiêu chí | Điểm (1-5) |
|---|---|
|Problem-solution fit| 5 |
|AI product thinking| 4 |
|Demo quality| 4 |

**Điều làm tốt:**
- Phân loại được các ngưỡng chỉ số 
- Có giải quyết được các chỉ số không thuộc database

**Gợi ý cải thiện:**
- Tuy nhiên thì ngưỡng chỉ số bị cố định ở dữ liệu quốc tế nên nếu như xét trong Việt Nam có thể sẽ bị lệch kha khá
- Chưa xử lý được fallback khi mà model bị dính rate limit exceeded

## Bàn B6: 
|Tiêu chí | Điểm (1-5) |
|---|---|
|Problem-solution fit|2 |
|AI product thinking|3|
|Demo quality|4 |

**Điều làm tốt:**
- Demo tốt, xử lý được các trường hợp AI không chắc chắn hay AI sai

**Gợi ý cải thiện:**
- Chưa tìm được metric đánh giá chatbot
- Database crawl từ web của Vinmec nên dữ liệu sẽ không được cập nhật nhanh

## Bàn A5:
|Tiêu chí | Điểm (1-5) |
|---|---|
|Problem-solution fit|4 |
|AI product thinking|3 |
|Demo quality|4 |

**Điều làm tốt:**
- Spec chi tiết, tương đối đủ, khả năng phản hồi nhanh tư vấn cho phép người dùng nhiều lựa chọn linh hoạt theo yêu cầu, có phản hồi hỏi thêm khi thiếu thông tin

**Gợi ý cải thiện:**
- Phần dự đoán bệnh yếu, gần như khó có thể sử dụng
- Demo chưa có dự đoán sâu, chưa chủ động hỏi lại người dùng
- Chưa xử lý tốt vấn đề đặt lịch xong hủy, đặt lịch nhưng không tới khám.
- Đặt lịch có thể bị ảnh hưởng bởi người đến trước -> Gây trải nghiệm xấu cho người dùng.
- Không có feedback

## Bàn A4:
|Tiêu chí | Điểm (1-5) |
|---|---|
|Problem-solution fit|4 |
|AI product thinking| 4|
|Demo quality|3 |

**Điều làm tốt:**
- Match chuyên khoa riêng với bệnh (biểu hiện bệnh nhân)

**Gợi ý cải thiện:**
- Không giải quyết được quá nhiều vấn đề do dựa dẫm vào bệnh nhân
- Chỉ mới demo được phần chatbot
- Chưa có feedback từ người dùng
- Metric dựa vào tiêu chuẩn vàng của bác sĩ
- Chưa có phản hồi hỏi bệnh nhân
- Tự động đặt lịch dựa vào cảm giác bệnh nhân -> Nguy hiểm
- Accuracy 90% -> khá thấp cho bệnh viện
- Chưa rõ ràng về tiêu chí
