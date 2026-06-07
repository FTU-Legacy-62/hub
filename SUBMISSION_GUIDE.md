# Hướng dẫn nộp bài cuối kỳ môn NHA408E khóa 62

Tài liệu này hướng dẫn các nhóm nộp bài cuối kỳ môn NHA408E khóa 62 qua GitHub organization `FTU-Legacy-62`.

## Mục đích của organization và hub

Organization `FTU-Legacy-62` là không gian chung để lưu repo sản phẩm cuối kỳ của cả lớp.

Repo `FTU-Legacy-62/hub` là nơi tập trung đường dẫn, hướng dẫn, mẫu tài liệu và trạng thái nộp bài của 10 nhóm.

Hub giúp giảng viên và sinh viên:

- Tìm nhanh repo của từng nhóm.
- Biết nhóm đã nộp gì và còn thiếu gì.
- Có mẫu thống nhất để mô tả sản phẩm, quá trình làm việc và đóng góp cá nhân.
- Lưu lại dấu vết học tập để các khóa sau có thể tham khảo.

## Repo nhóm dùng để làm gì

Mỗi nhóm có một repo riêng trong organization:

- G01: https://github.com/FTU-Legacy-62/G01
- G02: https://github.com/FTU-Legacy-62/G02
- G03: https://github.com/FTU-Legacy-62/G03
- G04: https://github.com/FTU-Legacy-62/G04
- G05: https://github.com/FTU-Legacy-62/G05
- G06: https://github.com/FTU-Legacy-62/G06
- G07: https://github.com/FTU-Legacy-62/G07
- G08: https://github.com/FTU-Legacy-62/G08
- G09: https://github.com/FTU-Legacy-62/G09
- G10: https://github.com/FTU-Legacy-62/G10

Repo nhóm là nơi lưu sản phẩm cuối kỳ và tài liệu đi kèm.

Nhóm cần đưa vào repo những gì cần thiết để người khác có thể mở, xem, hiểu và demo sản phẩm.

## Sản phẩm cuối kỳ cần có gì

Mỗi nhóm phải nộp sản phẩm thật, không chỉ nộp slide thuyết trình.

Sản phẩm có thể là ứng dụng, website, dashboard, mô hình thử nghiệm, quy trình phân tích dữ liệu, prototype tương tác hoặc một sản phẩm số khác phù hợp với đề tài.

Sản phẩm cần thể hiện rõ:

- Vấn đề nhóm muốn giải quyết.
- Người dùng mục tiêu.
- Mô tả sản phẩm.
- Input của sản phẩm.
- Logic hoặc quy tắc xử lý.
- User flow.
- Output.
- Cách mở, chạy hoặc demo.
- Đóng góp của từng thành viên.

Sản phẩm không cần hoàn hảo, nhưng phải mở được, xem được, giải thích được và demo được.

## Yêu cầu public repo

Tất cả repo nhóm phải ở chế độ public để giảng viên, các nhóm khác và sinh viên khóa sau có thể xem được.

Trước khi nộp, nhóm cần kiểm tra lại repo của mình không chứa thông tin nhạy cảm.

Sau hạn nộp bài, giảng viên có thể thay đổi quyền chỉnh sửa để lưu lại bản nộp chính thức.

## Yêu cầu an toàn dữ liệu

Không upload lên GitHub:

- API key.
- Mật khẩu.
- Token truy cập.
- Dữ liệu cá nhân.
- Dữ liệu riêng tư.
- File nội bộ.
- Bất kỳ file nào nhóm không có quyền công khai.

Nếu sản phẩm có sử dụng dữ liệu, nhóm phải ghi rõ dữ liệu đó là:

- Dữ liệu công khai.
- Dữ liệu giả lập.
- Dữ liệu tự tạo.
- Dữ liệu lấy từ nguồn khác.

Nếu dữ liệu lấy từ nguồn khác, nhóm cần ghi rõ nguồn và cách sử dụng ở mức đủ để người đọc hiểu.

## Yêu cầu footprint

Footprint là dấu vết học tập và đóng góp mà nhóm để lại cho người đọc sau này.

Footprint không chỉ là danh sách công việc.

Repo nhóm cần có:

- `README.md`: mặt tiền của sản phẩm, giúp người đọc bên ngoài hiểu nhanh sản phẩm là gì và mở như thế nào.
- `GROUP_FOOTPRINT.md`: dấu vết của cả nhóm, mô tả cách nhóm xây sản phẩm, lựa chọn đã đưa ra, điều học được, hạn chế và hướng tiếp tục.
- `INDIVIDUAL_FOOTPRINT.md`: dấu vết cá nhân của từng thành viên, mô tả đóng góp cụ thể, bằng chứng đóng góp và điều cá nhân học được.

Nhóm có thể dùng các mẫu trong hub:

- `GROUP_README_TEMPLATE.md`
- `GROUP_FOOTPRINT_TEMPLATE.md`
- `INDIVIDUAL_FOOTPRINT_TEMPLATE.md`

## Quy trình nộp bài đề xuất

1. Đưa sản phẩm và tài liệu cần thiết vào repo nhóm.
2. Tạo hoặc cập nhật `README.md`.
3. Tạo hoặc cập nhật `GROUP_FOOTPRINT.md`.
4. Tạo hoặc cập nhật `INDIVIDUAL_FOOTPRINT.md`.
5. Kiểm tra repo đang public.
6. Kiểm tra sản phẩm có thể mở, xem, chạy hoặc demo được.
7. Kiểm tra không có dữ liệu nhạy cảm hoặc file không được phép công khai.
8. Cập nhật trang `submissions/Gxx.md` trong hub nếu giảng viên yêu cầu nhóm tự điền trạng thái.

## Checklist cuối cùng cho nhóm

- Repo nhóm đã public.
- Sản phẩm thật đã được đưa lên repo.
- Sản phẩm không chỉ là slide thuyết trình.
- Có `README.md`.
- Có `GROUP_FOOTPRINT.md`.
- Có `INDIVIDUAL_FOOTPRINT.md`.
- README mô tả rõ sản phẩm và cách mở hoặc chạy.
- Group footprint mô tả rõ vấn đề, người dùng mục tiêu, input, logic xử lý, user flow, output, demo, lựa chọn thiết kế, hạn chế và bài học.
- Individual footprint có mục riêng cho từng thành viên.
- Mỗi thành viên có bằng chứng đóng góp cụ thể.
- Không có API key, mật khẩu, token, dữ liệu cá nhân, dữ liệu riêng tư hoặc file không được phép công khai.
- Nếu có dữ liệu, đã ghi rõ loại dữ liệu và nguồn dữ liệu.
