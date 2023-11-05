 # BEM
 - Là tiêu chuẩn đặt tên class khi viết CSS

## Ý nghĩa:
- Viết tắt của: Block Element Modifier
- Block: Khối
- Element: Thánh phần trong khối
- Modifier: Bổ sung ý nghĩa cho `Block` hoặc `Element`

## Tại sao phải dùng BEM?
- Mỗi người một kiểu
- Members đặt class trùng nhay, CSS đè lên nhau

# Cú pháp

- .block
- .block__element
- .block__element--modifier

## Tính ứng dụng

- Xây dựng layout website
- Xây dựng thành phần trên website

## Ưu điểm

- Tính rõ ràng
- Tải sử dụng dễ dàng
- Giúp cả team làm việc với nhau dễ dàng
- Tính Module, không lo CSS của class này ảnh hưởng lên
CSS của class khác 

## Nhược điểm

- Tên class dài
- Một số người cho là xấu

## Khi nào dùng BEM là phù hợp 

- Dự án nhiều mếm
- Dự án lớn, số lượng pages nhiểu hoặc số lượng các thành phần trên giao diện nhiều

## Thực hành

- Làm Button
    - Enable: Pointer, hover effect
    - Disabled: Arrow, no effect 
- Làm message
- Làm 1 thành phần trên website
