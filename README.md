# Phần giới thiệu
Họ và tên: Kiều Tấn Phước

Lớp: Da22TTB

MSSV: 110122144

Giáo viên hướng dẫn: Nguyễn Nhứt Lam
_______________________________________
# phần đề tài
Tên đề tài: tìm hiểu mô phỏng PageRank
______________________________________
# mô tả đề tài
phần giới thiệu PageRank:
PageRank là một thuật toán được Google phát triển để xếp hạng các trang web trong kết quả tìm kiếm. Thuật toán này do Larry Page và Sergey Brin (đồng sáng lập Google) giới thiệu vào năm 1996.Nó hoạt động dựa trên một ý tưởng cơ bản: một trang web càng nhận được 
nhiều liên kết từ các trang chất lượng khác, thì càng được đánh giá cao.
# Nguyên lý hoạt động:
- Mỗi trang web được xem như một nút (node) trong đồ thị, và các liên kết (links) giữa các trang là các cạnh (edges).
- Giá trị PageRank của một trang phản ánh tầm quan trọng của trang đó.
- Một trang sẽ "chia sẻ" giá trị PageRank của mình cho các trang mà nó liên kết đến.
- Nếu một trang nhận được liên kết từ một trang quan trọng, thì giá trị PageRank của nó cũng sẽ tăng lên.
# Công thức tính:
​![Ảnh chụp màn hình 2024-11-15 153648](https://github.com/user-attachments/assets/53652db6-9a56-475a-a620-fc182609d311)

PR(A) là điểm PageRank của trang A

d là hệ số giảm thiểu, thường là 0.85, mô phỏng khả năng người dùng ngừng tìm kiếm tại trang hiện tại

Li là các trang có liên kết đến trang A

𝐶 (𝐿𝑖) C(Li) là số lượng liên kết ra từ 𝐿𝑖
# ứng dụng thực tiển

- Xếp hạng trang web: PageRank giúp Google và các công cụ tìm kiếm khác xếp hạng các trang web.
- Phân tích mạng lưới: Dùng trong phân tích mạng xã hội hoặc các hệ thống liên kết.
- Phân tích trang quan trọng trong hệ thống lớn: Ứng dụng trong ngành khoa học dữ liệu và phân tích mạng lưới phức tạp
  
 # kết luận
Tầm quan trọng của PageRank: Thuật toán này không chỉ giúp sắp xếp thông tin trên Internet mà còn có thể áp dụng trong nhiều lĩnh vực phân tích khác
Những cải tiến: Với sự phát triển của công nghệ, thuật toán PageRank đã được mở rộng và cải tiến, nhưng nguyên tắc cơ bản vẫn được sử dụng rộng rãi
___________________________________________________________________________________________________________________________________________

# Phương pháp thực hiện

-Tìm hiểu thuật toán PageRank: Nghiên cứu nguyên lý  hoạt động của thuật toán cách tính toán và xếp hạng cho các trang web dựa trên liên kết 
-Xây dụng mô phỏng PageRank: Lập trình mô Phỏng thuật toán PageRank bằng ngôn ngữ Python hoặc C++
-Kiểm tra mô phỏng và điều chỉnh: Chạy thử mô phỏng trên tập dữ liệu nhỏ và điều chỉnh lại thuật toán để đạt được kết quả chính xác 
-Phân tích và đưa ra kết quả: So sánh kết quả xếp hạng của mô phỏng thực tế hoặc dữ liệu để đánh giá kết quả
___________________________________________________________________________________________________________________________________________
# Kết quả đạt được 
- biết được kiến thức cơ bản của thuật toán
- tìm hiểu được các ứng dụng mô phỏng thuật toán pagerank
- sử dụng được ứng dụng mô phỏng thuật toán page rank
- thử nghiệm được thuật toán và thành công
- mô phỏng thuật toán rõ ràng như yêu cầu
- kiểm tra lại kết quả lại lần nữa để được kết quả tốt trước khi nộp đồ án
____________________________________________________________________________________________________________________________________________
# phần cài đặt ứng dụng yêu cầu:
1. visual studio code
2. cài đặt thư viện python (networkX)
3. cài đặt phần mở rộng của thư viện và phần ứng dụng mô phỏng ( jupyter trên visual studio code )
4. cài đặt anaconda để liên kết juypyter qua vscode và thư viện python

![images](https://github.com/user-attachments/assets/b9f999ac-fcf1-4b51-9def-73e8053ed6d8)   X 
![Anaconda_Logo](https://github.com/user-attachments/assets/bb793625-307f-40d7-9c4a-15438ceaccdc)    X
<img width="256" alt="tzt4j7ih7s5cmi65rbstq4q4byrn" src="https://github.com/user-attachments/assets/4805a919-9787-45a4-a4cd-4fd031ae7dd3">

_______________________________________________________________________________________________________________________
# sử dụng ngôn ngữ
python
____________________________________________________________________________________________________________________________________________
# Phần liên hệ
EMAIL: 110122144@st.tvu.edu.vn

ZALO: 0854377830 

​

