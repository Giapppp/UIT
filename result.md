# BÁO CÁO VỀ THUẬT TOÁN SẮP XẾP #

#### Họ và Tên: Vũ Tiến Giáp ####
#### MSSV: 22520367 ####

### 1. Merge sort ###
#### Mô tả ####
- Sắp xếp trộn hoạt động kiểu đệ quy:
  - Đầu tiên chia dữ liệu thành 2 phần, và sắp xếp từng phần.
  - Sau đó gộp 2 phần lại với nhau. Để gộp 2 phần, ta làm như sau:
    - Tạo một dãy A mới để chứa các phần tử đã sắp xếp. 
    - So sánh 2 phần tử đầu tiên của 2 phần. Phần tử nhỏ hơn ta cho vào A và xóa khỏi phần tương ứng.
    - Tiếp tục như vậy đến khi ta cho hết các phần tử vào dãy A.
##### a) Ưu điểm
- Chạy nhanh, độ phức tạp $O(NlogN)$
- Ổn định
##### b) Nhược điểm #####
- Cần dùng thêm bộ nhớ để lưu mảng trung gian

### 2. Quick sort ###
#### Mô tả ####
- Chia dãy thành 2 phần, một phần "lớn" và một phần "nhỏ".
  - Chọn một khóa pivot
  - Những phần tử lớn hơn pivot chia vào phần lớn
  - Những phần tử nhỏ hơn hoặc bằng pivot chia vào phần nhỏ.
- Gọi đệ quy để sắp xếp 2 phần.
##### a) Ưu điểm
- Chạy nhanh (nhanh nhất trong các thuật toán sắp xếp dựa trên việc só sánh các phần tử). Độ phức tạp $O(NlogN)$
##### b) Nhược điểm #####
- Trong trường hợp tệ nhất, thuật toán quicksort có độ phức tạp là $O(N^2)$

### 3. Heap sort ###
#### Mô tả ####
- Ta lưu mảng vào CTDL Heap.
- Ở mỗi bước, ta lấy ra phần tử nhỏ nhất trong heap, cho vào mảng đã sắp xếp.
##### a) Ưu điểm
- Cài đặt đơn giản nếu đã có sẵn thư viện Heap.
- Chạy nhanh, độ phức tạp $O(NlogN)$.
##### b) Nhược điểm #####
- Không ổn định

### 4. std::sort ###
#### Mô tả ####
- Đây là một thuật toán Introsort sắp xếp được kết hợp bởi 3 thuật toán sắp xếp khác nhau là Quicksort, Heapsort và Selectionsort. Các thuật toán như Heapsort và Selectionsort được sử dụng để loại bỏ các trường hợp tệ nhất của quicksort.

## KẾT QUẢ THỰC NGHIỆM ##
Bảng thời gian chạy(tính theo milisecond)<br />

![image](https://github.com/Giapppp/UIT/blob/main/table1.png)<br />

Biểu đồ thời gian<br b/>

![image](https://github.com/Giapppp/UIT/blob/main/chart.png)





