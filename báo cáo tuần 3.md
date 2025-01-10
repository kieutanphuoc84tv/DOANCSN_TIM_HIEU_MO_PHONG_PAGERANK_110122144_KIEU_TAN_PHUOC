# Giới thiệu
Họ và tên: Kiều Tấn Phước

Lớp: Da22TTB

MSSV: 110122144

Giáo viên hướng dẫn: Nguyễn Nhứt Lam

# Phần chính báo cáo

- Từ ngày 02/12/2024 đến 08/12/2024

Hôm nay em xin báo cáo tiến độ đồ án về thuật toán mô phỏng PAGERANK của em như sau:

> Mục tiêu:
- Hoàn thiện mô phỏng thuật toán PageRank (biểu đồ 2D)
- Thêm trực quan hóa (tên nút, trọng số) vào biểu đồ bằng matplotlib hoặc Dash.
- Đảm bảo lại sơ đồ 2D được vẽ đúng bằng thư viện như networkx.
- Viết báo cáo rõ ràng từng bước thực hiện.
- Rà sót lại xem có bị lỗi khi chạy mô phỏng

> Kết Quả:
- Đã thực hiện được tên nút và trọng số rõ ràng trên biểu đồ để nhận biết được các nút liên kết
- Đã thực hiện sơ đồ 2D bằng thư viện networkX
- Đã viết báo cáo từng bước 70%
- rà sót lại quá trình không phát hiện lỗi

> Khó khăn:
trong phần mô phỏng thuật toán thì em có khó khăn như sau:
- xây dựng các nút đôi khi không giống với biểu đồ 2D
- mô phỏng không đúng trình tự logic
> khắc phục

- Xây dựng các nút không giống với biểu đồ 2D:

Em đã rà soát lại logic trong việc khai báo và định nghĩa các nút cùng với trọng số. Để đảm bảo sơ đồ 2D đúng với biểu đồ lý thuyết em sử dụng thư viện networkX với cách định nghĩa đồ thị cụ thể em cũng kiểm tra kỹ đầu vào của các nút và cạnh trước khi chuyển sang mô phỏng.

- Mô phỏng không đúng trình tự logic:

Em đã kiểm tra và tối ưu lại thuật toán tính toán thứ hạng PageRank đồng thời em đã bổ sung thêm kiểm tra đầu ra qua từng bước để đảm bảo thứ tự các bước logic được thực hiện đúng thông qua việc sử dụng biểu đồ 2D và làm đối chiếu em có thể xác minh tính chính xác của kết quả.

# phần hình ảnh và mô tả

phần mục code và hình ảnh của em đã thực hiện như sau: 

![image](https://github.com/user-attachments/assets/bbd04a4f-19a0-4d45-a8bd-c91f341bd78b)

-----------------------------------------------------------------------------------------------------------------

Tính năng chính:

   - Đoạn code và kết quả mô phỏng thể hiện rõ ràng mục tiêu chính là trực quan hóa thuật toán PageRank.    
   - Các giá trị PageRank được chú thích cụ thể hỗ trợ kiểm tra nhanh kết quả đầu ra của thuật toán.

 > mô tả
trong phần mô tả này thì em đã sử dụng thư viện ploty và networkX để xây dựng thuật toán mô phỏng pageRank hoàn chỉnh để em có thể xem các nút cạnh (edges) hoàn toàn rõ ràng và dễ hiểu nhất
  
| hình ảnh thư viện Ploty
![image](https://github.com/user-attachments/assets/804a706d-2371-436f-912a-fc36c731ac23)

Do đó em có thể thấy được biểu đồ mô phỏng PageRank

# phần mục tuần kế tiếp

- Cố gắng hoàn thiện sản phẩm mô phỏng PAGERANK
- Tìm và rà soát lại biểu đồ và trình tự logic
- Tìm lỗi sai phát sinh khi đang quá trình nghiên cứu
- Hoàn thành báo cáo mô phỏng Page Rank
- Hoàn thành báo cáo tuần

> SINH VIÊN THỰC HIỆN

KIỀU TẤN PHƯỚC









