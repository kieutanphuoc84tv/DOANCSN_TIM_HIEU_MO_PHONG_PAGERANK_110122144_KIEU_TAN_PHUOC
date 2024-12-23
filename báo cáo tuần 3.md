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
- Đã hoàn thiện được mô phỏng thuật toán PAGERANK 2D và biểu đồ cột
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

Em đã kiểm tra và tối ưu lại thuật toán tính toán thứ hạng PageRank đồng thời em đã bổ sung thêm kiểm tra đầu ra qua từng bước để đảm bảo thứ tự các bước logic được thực hiện đúng thông qua việc sử dụng biểu đồ 2D và biểu đồ cột làm đối chiếu em có thể xác minh tính chính xác của kết quả.

# phần hình ảnh và mô tả

phần mục code và hình ảnh của em đã thực hiện như sau: 

![image](https://github.com/user-attachments/assets/bbd04a4f-19a0-4d45-a8bd-c91f341bd78b)

-----------------------------------------------------------------------------------------------------------------

> mô tả :

- Hình ảnh đầu tiên (Code Python thực hiện mô phỏng PageRank):

    Đây là đoạn mã nguồn em đã sử dụng để thực hiện mô phỏng thuật toán PageRank.
    Đoạn mã bao gồm hai phần chính:
  
  Biểu đồ cột PageRank: 

Hiển thị thứ hạng của từng nút (node) bằng các cột với giá trị PageRank được chú thích ngay trên từng cột để dễ dàng quan sát.
  Biểu đồ 2D Network: Mô phỏng mạng lưới các nút và liên kết (edges) giữa chúng sử dụng thư viện networkX để định vị các nút các giá trị PageRank cũng được hiển thị bằng số màu đỏ gần từng nút.

- Hình ảnh thứ hai (Kết quả đầu ra mô phỏng PageRank):

    Hình này thể hiện kết quả trực quan hóa PageRank:
  
  Phần bên trái là biểu đồ cột, hiển thị thứ hạng của các nút (node) dựa trên giá trị PageRank các nút được sắp xếp theo thứ tự, giúp dễ dàng nhận biết node nào có ảnh hưởng lớn nhất trong mạng lưới.
  Phần bên phải là sơ đồ mạng 2D của thuật toán PageRank. Các nút được bố trí trên không gian 2D theo thuật toán định vị của networkX các giá trị PageRank được hiển thị rõ ràng gần mỗi nút cho phép đối chiếu với biểu đồ cột để kiểm tra tính chính xác.

Tính năng chính:

   - Đoạn code và kết quả mô phỏng thể hiện rõ ràng mục tiêu chính là trực quan hóa thuật toán PageRank.
    
   - Biểu đồ cột cung cấp cách nhìn toàn cảnh về giá trị PageRank của các nút trong khi sơ đồ mạng lưới 2D giúp hiểu rõ hơn về mối liên hệ giữa các nút.
    
   - Các giá trị PageRank được chú thích cụ thể hỗ trợ kiểm tra nhanh kết quả đầu ra của thuật toán.

> Phần thuật toán mô phỏng 3D

về phần này em đã nghiên cứu tập trung phần 3D sao cho đúng với phần mô phỏng PAGERANK 2D


 > mô tả
- Trong phần mô phỏng PageRank này em đã sử dụng các đồ thị 2D và 3D để minh họa các liên kết và thứ tự ảnh hưởng của các nút trong mạng việc sử dụng mô phỏng 3D giúp người dùng dễ dàng nhìn thấy các quan hệ giữa các nút từ nhiều góc độ khác nhau từ đó đưa ra những đánh giá chính xác hơn về tầm quan trọng của từng nút đồ thị 2D lại cung cấp một cái nhìn đơn giản dễ hiểu về cấu trúc của mạng và sự phân bổ của các giá trị PageRank.

- Để thực hiện mô phỏng này, em đã sử dụng thư viện Dash để xây dựng giao diện người dùng tương tác kết hợp với Plotly để tạo các biểu đồ và trực quan hóa dữ liệu Dash cho phép em dễ dàng tạo các ứng dụng web để người dùng có thể tương tác trực tiếp với dữ liệu, thay đổi các tham số và quan sát sự thay đổi của các giá trị PageRank trong thời gian thực mô hình này không chỉ giúp nâng cao hiệu quả trong việc phân tích mạng mà còn hỗ trợ người dùng trong việc đánh giá, nhận định các liên kết trong các hệ thống phức tạp.
  
| hình ảnh thư viện DASH

![ảnh](https://github.com/user-attachments/assets/b0de890c-385f-4cf6-9721-4900705bd9a9)

phần thư viện này đã giúp cho em liên kết được trang web của DASH bằng cách click chuột vào ID trên thanh terminal của visual code 

![Screenshot 2024-12-13 231259](https://github.com/user-attachments/assets/12dee205-0f98-4b2e-93ca-9d1db83960e3)

Do đó em có thể thấy được biểu đồ 3D và 2D PAGERANK

# phần mục tuần kế tiếp

- Cố gắng hoàn thiện sản phẩm mô phỏng PAGERANK
- Tìm và rà soát lại biểu đồ và trình tự logic
- Tìm lỗi sai phát sinh khi đang quá trình nghiên cứu
- Hoàn thành báo cáo mô phỏng Page Rank
- Hoàn thành báo cáo tuần

> SINH VIÊN THỰC HIỆN

KIỀU TẤN PHƯỚC









