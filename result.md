# BÁO CÁO VỀ THUẬT TOÁN SẮP XẾP #

#### Họ và Tên: Vũ Tiến Giáp ####
#### MSSV: 22520367 ####

### 1. Merge sort ###
#### Mô tả ####
Giống như Quick sort, Merge sort là một thuật toán chia để trị. Thuật toán này chia mảng cần sắp xếp thành 2 nửa. Tiếp tục lặp lại việc này ở các nửa mảng đã chia. Sau cùng gộp các nửa đó thành mảng đã sắp xếp.
##### a) Ưu điểm
- Chạy nhanh, độ phức tạp $O(NlogN)$
- Ổn định
##### b) Nhược điểm #####
- Cần dùng thêm bộ nhớ để lưu mảng trung gian

### 2. Quick sort ###
#### Mô tả ####
- Chia mảng thành hai phần bằng cách so sánh từng phần tử của mảng với một phần tử được gọi là phần tử chốt. Một mảng bao gồm các phần tử nhỏ hơn hoặc bằng phần tử chốt và một mảng gồm các phần tử lớn hơn phần tử chốt.

- Quá trình phân chia này diễn ra cho đến khi độ dài của các mảng con đều bằng 1. Với phương pháp đệ quy ta có thể sắp xếp nhanh các mảng con sau khi kết thúc chương trình ta được một mảng đã sắp xếp hoàn chỉnh.
##### a) Ưu điểm
- Chạy nhanh (nhanh nhất trong các thuật toán sắp xếp dựa trên việc só sánh các phần tử). Độ phức tạp $O(NlogN)$
##### b) Nhược điểm #####
- Trong trường hợp tệ nhất, thuật toán quicksort có độ phức tạp là $O(N^2)$

### 3. Heap sort ###
#### Mô tả ####
Heap sort là kỹ thuật sắp xếp dựa trên so sánh dựa trên cấu trúc dữ liệu Binary Heap. Nó tương tự như sắp xếp lựa chọn, nơi đầu tiên chúng ta tìm phần tử lớn nhất và đặt phần tử lớn nhất ở cuối. Chúng ta lặp lại quá trình tương tự cho các phần tử còn lại
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





