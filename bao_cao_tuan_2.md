# GIỚI THIỆU

Họ và Tên: KIỀU TẤN PHƯỚC

LỚP:DA22TTB

MSSV: 110122144

GIÁO VIÊN HƯỚNG DẪN: NGUYỄN NHỨT LAM

------------------------------------------------------------
# PHẦN NỘI DUNG BÁO CÁO TUẦN 2 | 18/11/2024 - 24/11/2024

Trong tuần trước em đã khai báo về nội dung của đồ án PAGERANK và cách thực hiện cài đặt phần mềm mô phỏng hôm nay em xin báo cáo đồ án tuần thứ 2 cho thầy:
> Mục tiêu
-	Tiếp tục nghiên cứu ngôn ngữ lập trình và tìm hiểu thêm về các mô phỏng 
-	Nghiên cứu thêm về các kiến thức cơ bản của thuật toán để mô phỏng và kiểm tra mô phỏng
-	Xây dựng mô phỏng trên visual studio code
-	Sử dụng mô phỏng lập trình và kiểm tra lại mô phỏng

> Kết quả 
-	Xây dựng được thành công phần mô phỏng PAGERANK theo sơ đồ 2D
-	Biết được kiến thức cơ bản của thuật toán và nắm bắt được cách sử dụng mô phỏng
-	Xây dựng được mô phỏng 2D trên visual studio code 
-	Kiểm tra mô phỏng kết quả đạt được thành công

> khó khăn
trong việc xây dựng mô phỏng thì gặp các vấn đề như:
- Lỗi trong mô phỏng PageRank 
-	Sai logic thuật toán PageRank trong code.
-	Dữ liệu đầu vào không phù hợp.
-	Biểu đồ không được cấu hình đúng cách khi hiển thị.
  
> sau đây là hình ảnh bị lỗi mô phỏng
- phần mục code:
  
![image](https://github.com/user-attachments/assets/c4d8cb80-2df3-4ec7-8964-61b7e8ebfaed)



- phần hình ảnh:
  
![image](https://github.com/user-attachments/assets/2ab2d508-f3db-4996-af78-185d4f1c1705)


> mô tả phần lỗi:

- Không hiển thị số liệu trọng số: Các cạnh trong biểu đồ không có giá trị nào được hiển thị.
  
- Không hiển thị điểm PageRank: Không có con số nào hiển thị trên các nút gây khó khăn khi phân tích.
  
- Mô phỏng không hoàn chỉnh: Thiếu cả thông tin trọng số và điểm PageRank đồ thị trở nên thiếu ý nghĩa và không hỗ trợ việc phân tích mối quan hệ giữa các nút.

  > lý do lỗi mô phỏng:
  
- Không rõ ràng trong trực quan hóa: Do không hiển thị số liệu nào, người dùng không thể hiểu logic hoặc thông tin trong đồ thị.
- Không phù hợp để kiểm chứng thuật toán: Mô phỏng này không cung cấp thông tin cần thiết để đánh giá hoặc xác nhận cách hoạt động của thuật toán PageRank.

  > phần sau khi sửa lỗi

  ![image](https://github.com/user-attachments/assets/f711dc6d-97e6-483f-9425-886c7b3d1892)

  ![image](https://github.com/user-attachments/assets/7c7b0bf7-1ad4-4764-9505-12a7e85abc16)


  
> kinh nghiệm

Tầm quan trọng của dữ liệu đầu vào:

- Khi không gán trọng số hoặc không thêm thông tin cần thiết vào các cạnh, mô phỏng trở nên không rõ ràng và thiếu chính xác.
  
- Cần kiểm tra kỹ dữ liệu đầu vào đặc biệt là trọng số giữa các nút trong đồ thị.

Cách xử lý lỗi trực quan hóa:

- Để biểu đồ trực quan và dễ hiểu hơn cần thêm các thông tin cần thiết như nhãn trọng số và giá trị PageRank lên các nút.

- Thiếu các thông tin này sẽ gây khó khăn cho người dùng trong việc phân tích kết quả.

kiểm tra logic thuật toán:

- Mặc dù thuật toán PageRank vẫn hoạt động khi thiếu trọng số nhưng kết quả có thể không phản ánh đúng ý định thực tế. Việc gán trọng số hợp lý sẽ làm kết quả mô phỏng chính xác và sát thực tế hơn.

  kiểm tra lại tất cả lỗi khi chạy

- vì lý do khi chạy sẽ phát sinh ra vấn đề mất đi số nút và các liên kết các nút khác nên phải kiểm tra phần code có bị sai hoặc thiếu khi lập trình mô phỏng PAGERANK

# Kế hoạch tuần tiếp theo

-	Hoàn thiện mô phỏng thuật toán PageRank (biểu đồ 2D)
- thêm các biểu đồ trực quan như biểu đồ cột và mô phỏng 3D
-	 Thêm trực quan hóa (tên nút, trọng số) vào biểu đồ bằng matplotlib hoặc Dash.
-	 Đảm bảo lại sơ đồ 2D được vẽ đúng bằng thư viện như networkx.
-	Viết báo cáo rõ ràng từng bước thực hiện.
-	Rà sót lại xem có bị lỗi khi chạy mô phỏng 

# sinh viên thực hiện

KIỀU TẤN PHƯỚC



