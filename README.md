**Selecttion sort**

**Ý tưởng:** 
- Chọn phần tử nhỏ nhất trong N phần tử trong dãy hiện hành ban đầu
- Đưa phần tử này về đầu dãy hiện hanh
- Xét dãy hiện hành với N-1 phần tử, bắt đầu từ vị trí thứ 2
- Lặp lại cho đến khi dãy chỉ còn 1 phần tử

**Interchange sort**

**Ý tưởng:**
Xuất phát từ đầu dãy, xét các phần tử nghịch thế với nhau và đổi chỗ nó. Lặp lại cho đến khi còn 1 phần tử

**Bubble sort**

**Ý tưởng:** 
- Xuất phát từ đầu dãy, đổi chỗ các cặp phần tử kế cận để đưa phần tử lớn hơn trong cặp phần tử đó về đúng vị trí cuối dãy hiện hành
- Xét từng cặp phần từ và bỏ đi phần tử đã đưa ra cuối dãy hiện hành
- Lặp lại cho đến khi không còn cặp phần tử nào để xét

**Insertion sort**
  
**Ý tưởng:**
- Một mảng được chia thành hai đoạn: đoạn được sắp xếp và chưa được sắp xếp
- Trong mỗi lần chạy phần tử đầu tiên của đoạn chưa đoạn sắp xếp được chọn để chèn vào vị trí thích hợp trong đoạn đã được sắp xếp
- Mảng có n phần tử sẽ tốn n-1 lần chạy để sắp xếp

**Quick sort**
    
**Ý tưởng:**
- Phân hoạch dãy ban đầu thành 3 phần với pivot là giá trị của một phần tử tùy ý trong dãy ban đầu (S1, pivot, S2)
- Nếu S1 và S2 chỉ còn 1 phần tử thì dãy ban đầu đã được sắp xếp
- Nếu S1 và S2 có nhiều hơn 1 phần tử thì tiến hành phân hoạch như các bước ở trên

**Heap sort**   

**Ý tưởng:**
- Build-Heap để tạo dãy Heap cho dãy A với N phần tử
- Sau đó hoán đổi vị trí phần tử đầu và cuối. Xét dãy Heap khi đã loại bỏ phần tử cuối cùng. Tiếp theo Heapify lại phần tử A[0] để đưa dãy về dãy có dạng tính chất Heap. Lặp lại cho đến khi còn 1 phần tử

**Merge sort**
    
**Ý tưởng:**
    
- Chia mảng ban đầu thành 2 mảng con, rồi tiếp tục chia 2 mảng con thành 2 mảng con nữa, lặp lại cho đến khi mảng con chỉ có 1 phần tử
- Hợp các mảng con lại với nhau bằng thao tác merge để tạo ra mảng đã được sắp xếp
