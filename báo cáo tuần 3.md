# Giới thiệu
Họ và tên: Kiều Tấn Phước

Lớp: Da22TTB

MSSV: 110122144

Giáo viên hướng dẫn: Nguyễn Nhứt Lam

# Phần chính báo cáo

- Từ ngày 02/12/2024 đến 08/12/2024

Hôm nay em sinh báo cáo tiến độ đồ án về thuật toán mô phỏng PAGERANK của em như sau:

> Mục tiêu:
- Hoàn thiện mô phỏng thuật toán PageRank (2D và biểu đồ cột).
- Hoàn thiện mô phỏng thuật toán và ứng dụng 3D.
- Thêm trực quan hóa (tên nút, trọng số) vào biểu đồ bằng matplotlib hoặc Dash.
- Đảm bảo sơ đồ 2D được vẽ đúng bằng thư viện như networkX.
- Viết báo cáo rõ ràng từng bước thực hiện.
- Rà sót lại xem có bị lỗi khi chạy mô phỏng

> Kết Quả:
- Đã hoàn thiện được mô phỏng thuật toán PAGERANK 2D và biểu đồ cột
- Đã thực hiện được mô phỏng trực quan hóa thuật toán 3D PAGERANK
- Đã thực hiện được tên nút và trọng số rõ ràng trên biểu đồ để nhận biết được các nút liên kết
- Đã thực hiện sơ đồ 2D bằng thư viện networkX
- Đã viết báo cáo từng bước 70%
- rà sót lại quá trình không phát hiện lỗi

> Khó khăn:
trong phần mô phỏng thuật toán thì em có khó khăn như sau:
- xây dựng các nút đôi khi không giống với biểu đồ 2D
- lỗi không di chuyển được mô phỏng ( như xoay ngang hoặc xoay dọc )
- mô phỏng không đúng trình tự logic
> khắc phục

- Xây dựng các nút không giống với biểu đồ 2D:

Em đã rà soát lại logic trong việc khai báo và định nghĩa các nút cùng với trọng số. Để đảm bảo sơ đồ 2D đúng với biểu đồ lý thuyết em sử dụng thư viện networkX với cách định nghĩa đồ thị cụ thể em cũng kiểm tra kỹ đầu vào của các nút và cạnh trước khi chuyển sang mô phỏng.

- Lỗi không di chuyển được mô phỏng (như xoay ngang hoặc xoay dọc):
  
Em đã sử dụng tính năng hỗ trợ xoay tự động của thư viện Dash 3D cụ thể em thêm chế độ camera rotation trong biểu đồ 3D cho phép người dùng điều chỉnh góc nhìn trực tiếp bằng chuột hoặc bàn phím.

- Mô phỏng không đúng trình tự logic:

Em đã kiểm tra và tối ưu lại thuật toán tính toán thứ hạng PageRank đồng thời em đã bổ sung thêm kiểm tra đầu ra qua từng bước để đảm bảo thứ tự các bước logic được thực hiện đúng thông qua việc sử dụng biểu đồ 2D và biểu đồ cột làm đối chiếu em có thể xác minh tính chính xác của kết quả.

# phần hình ảnh và mô tả

phần mục code và hình ảnh của em đã thực hiện như sau: 

![ảnh](https://github.com/user-attachments/assets/b07d3f65-fc5c-4976-9cae-e1afa452d4ca) 

--------------------------------------------------------------------------------------

![Figure_1](https://github.com/user-attachments/assets/bada16fd-2c16-47cc-a161-b9707e87406f)

> mô tả :

- Hình ảnh đầu tiên (Code Python thực hiện mô phỏng PageRank):

    Đây là đoạn mã nguồn em đã sử dụng để thực hiện mô phỏng thuật toán PageRank.
    Đoạn mã bao gồm hai phần chính:
  
  Biểu đồ cột PageRank: Hiển thị thứ hạng của từng nút (node) bằng các cột với giá trị PageRank được chú thích ngay trên từng cột để dễ dàng quan sát.
  Biểu đồ 2D Network: Mô phỏng mạng lưới các nút và liên kết (edges) giữa chúng sử dụng thư viện networkX để định vị các nút các giá trị PageRank cũng được hiển thị bằng số màu đỏ gần từng nút.

- Hình ảnh thứ hai (Kết quả đầu ra mô phỏng PageRank):

    Hình này thể hiện kết quả trực quan hóa PageRank:
  
  Phần bên trái là biểu đồ cột, hiển thị thứ hạng của các nút (node) dựa trên giá trị PageRank các nút được sắp xếp theo thứ tự, giúp dễ dàng nhận biết node nào có ảnh hưởng lớn nhất trong mạng lưới.
  Phần bên phải là sơ đồ mạng 2D của thuật toán PageRank. Các nút được bố trí trên không gian 2D theo thuật toán định vị của networkX các giá trị PageRank được hiển thị rõ ràng gần mỗi nút cho phép đối chiếu với biểu đồ cột để kiểm tra tính chính xác.

Tính năng chính:

   - Đoạn code và kết quả mô phỏng thể hiện rõ ràng mục tiêu chính là trực quan hóa thuật toán PageRank.
    
   - Biểu đồ cột cung cấp cách nhìn toàn cảnh về giá trị PageRank của các nút trong khi sơ đồ mạng lưới 2D giúp hiểu rõ hơn về mối liên hệ giữa các nút.
    
   - Các giá trị PageRank được chú thích cụ thể hỗ trợ kiểm tra nhanh kết quả đầu ra của thuật toán.




