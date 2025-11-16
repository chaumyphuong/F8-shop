# Bem
- Là tiêu chuẩn đặt tên class khi viết CSS

## Ý nghĩa:
- Block element modifier
- Block: Khối 
- element: thành phần trong khối
- modifier: bổ sung ý nghĩa cho 'block' hoặc 'element'

## tại sao phải dùng block
- mỗi người 1 kiểu
- members đặt class trùng nhau, CSS đè lên nhau

## cú pháp
- . block
- .block_element

- .block--modifier
- .block_element--modifier
 
 ## tính ứng dụng
 - xây dựng layout website
 - xây dựng thành phần trên website

 ## ưu điểm
 - tính rõ ràng 
 - tái sử dụng dễ dàng
 - giúp cả team làm việc với nhau dễ dàng
 - tính module, không lo CSS của class này ảnh hưởng lên CSS của class khác


 ## nhược điểm
 - tên class dài
 - 1 số người cho là xấu

 ## khi nào dùng BEM là phù hợp
 - dự án nhiều members
 - dự án lớn, số lượng pages nhiều hoặc số lượng các thành phần trên giao diện nhiều

 ## thực hành
 - làm button
    - enabled: pointer, hover effect
    - díabled: arrow, no effect
 - làm message
 - làm 1 thành phần trên website
