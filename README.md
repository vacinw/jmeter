# Báo Cáo Bài Tập Kiểm Thử Sử Dụng Apache JMeter

## I. Giới Thiệu

Mục tiêu của bài tập này là thực hiện kiểm thử hiệu suất và tải trọng cho một ứng dụng web sử dụng công cụ Apache JMeter. Ứng dụng web được chọn là Simplilearn, và nhiệm vụ của chúng ta là đánh giá hiệu suất của nó dưới các điều kiện tải trọng khác nhau.

## II. Mục Tiêu

1. **Đo lường thời gian phản hồi:** Kiểm tra và đo lường thời gian phản hồi của ứng dụng web khi có nhiều người dùng truy cập đồng thời.
2. **Phát hiện các vấn đề hiệu suất:** Xác định các vấn đề về hiệu suất như thời gian phản hồi chậm, lỗi ứng dụng và khả năng đáp ứng dưới tải trọng cao.

## III. Phương Pháp

1. **Xác định Yêu Cầu Kiểm Thử:**

   - Phân tích các yêu cầu chức năng của ứng dụng web.
   - Xác định các trường hợp sử dụng quan trọng cần được kiểm thử, chẳng hạn như đăng nhập, tìm kiếm và thao tác trên ứng dụng.

2. **Tạo Kịch Bản Kiểm Thử Trong JMeter:**

   - Sử dụng JMeter để tạo các kịch bản kiểm thử tương ứng với các trường hợp sử dụng đã xác định.
   - Mỗi kịch bản bao gồm các yêu cầu HTTP như đăng nhập, tìm kiếm và thực hiện các thao tác quan trọng khác.

3. **Cấu Hình Thread Group và Các Thành Phần Khác:**

   - Thiết lập số lượng người dùng (threads) và thời gian chạy cho mỗi kịch bản.
   - Cấu hình các Listener để ghi lại kết quả kiểm thử.

4. **Chạy Kiểm Thử và Thu Thập Kết Quả:**
   - Chạy kiểm thử trong JMeter dưới các điều kiện tải trọng khác nhau.
   - Thu thập và ghi lại kết quả của mỗi lần chạy, bao gồm thời gian phản hồi, số lỗi và các thống kê khác.

## IV. Kết Quả

1. **Thời Gian Phản Hồi Trung Bình:**

   - Xác định thời gian phản hồi trung bình của các yêu cầu trong các điều kiện tải trọng khác nhau.
   - Đây là chỉ số chính để đánh giá hiệu suất của ứng dụng.

2. **Tài Nguyên Tiêu Thụ:**

   - Đánh giá tài nguyên hệ thống như bộ nhớ và CPU tiêu thụ trong quá trình kiểm thử.
   - Điều này giúp xác định xem liệu ứng dụng có thể chịu tải trọng đó hay không.

3. **Các Vấn Đề Hiệu Suất:**
   - Phát hiện và mô tả các vấn đề hiệu suất, bao gồm thời gian phản hồi cao, lỗi ứng dụng và sự giảm sút hiệu suất dưới áp lực tải trọng.

## V. Đánh Giá và Kết Luận

Dựa trên kết quả kiểm thử, chúng tôi đã đánh giá hiệu suất của ứng dụng và phát hiện ra các vấn đề hiệu suất cụ thể. Từ đó, chúng tôi đề xuất các biện pháp cải thiện và tối ưu hóa để nâng cao hiệu suất của ứng dụng trong tương lai. Một số đề xuất bao gồm tối ưu hóa mã nguồn, cải thiện cấu hình máy chủ và sử dụng các công nghệ tối ưu hóa tải trọng như caching.

## VI. Tóm Tắt

Báo cáo này đã trình bày chi tiết về quá trình kiểm thử hiệu suất và tải trọng của ứng dụng web Simplilearn sử dụng Apache JMeter. Qua việc thực hiện kiểm thử dưới các điều kiện tải trọng khác nhau, chúng tôi đã thu thập được các thông tin quan trọng về thời gian phản hồi, tài nguyên tiêu thụ và các vấn đề hiệu suất. Những kết quả này sẽ giúp đưa ra các quyết định cải thiện và tối ưu hóa ứng dụng trong tương lai.
