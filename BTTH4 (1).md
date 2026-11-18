
# 1. Bối cảnh
Phân tích điểm kiểm tra của 5 sinh viên trong 3 tuần để tìm ra sinh viên có kết quả giảm sút.

# 2. Yêu cầu đầu ra
- Thiết kế prompt Chain-of-Thought (CoT).
- Lập bảng phân tích điểm.
- Đưa ra 3 nhận định và 3 giải pháp.

# 3. Bài làm

## Prompt
Bạn là trợ lý giảng viên. Hãy suy nghĩ từng bước, thực hiện theo trình tự: tính toán → so sánh → nhận định → đề xuất.

Dựa vào điểm 3 tuần của 5 sinh viên, hãy:
1. Tính chênh lệch điểm tuần 3 so với tuần 1.
2. Xác định sinh viên giảm điểm.
3. Đưa ra 3 nhận định và 3 giải pháp.
4. Chỉ sử dụng dữ liệu đã cho, không tự suy đoán nguyên nhân.

## Bước 1: Phân tích điểm

| Sinh viên | Tuần 1 | Tuần 2 | Tuần 3 | Thay đổi |
|---|---|---|---|---|
| An | 8 | 7 | 5 | -3 |
| Bình | 7 | 6 | 4 | -3 |
| Chi | 9 | 8 | 8 | -1 |
| Dũng | 6 | 5 | 3 | -3 |
| Hà | 8 | 8 | 7 | -1 |

Công thức: Điểm thay đổi = Tuần 3 - Tuần 1.

## Bước 2: Nhận định
1. An, Bình và Dũng đều giảm 3 điểm, có dấu hiệu sa sút rõ rệt.
2. Chi có điểm tuần 3 cao nhất (8 điểm).
3. Dũng có điểm tuần 3 thấp nhất (3 điểm).

## Bước 3: Thông tin cần xác minh
- Sinh viên có gặp khó khăn khi học lập trình không?
- Tần suất tham gia lớp học và làm bài tập thế nào?
- Đề kiểm tra các tuần có độ khó tương đương không?

## Bước 4: Giải pháp
1. Tổ chức học phụ đạo cho An, Bình và Dũng.
2. Giao bài tập thực hành phù hợp với từng sinh viên.
3. Kiểm tra hàng tuần để theo dõi tiến bộ.


