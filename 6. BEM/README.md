# BEM
- Là tiêu chuẩn khi đặt tên class khi viết CSS
# Ý nghĩa
- Viết tắt của: Block Element Modifier
- Block: Khối
- Element: Thành phần trong khối
- Modifier: Bổ sung ý nghĩa cho "block" và "element"
# Tại sao phải sử dung BEM
- Mỗi người đặt class một kiểu khó quản lý dễ bị trùng class -> ghi đề CSS lên nhau nên gây lỗi cho các class cùng tên
# Cú pháp
.block : thể hiện class
.block__element: Thể hện thẻ element trong block

.block--modifier: Thể hiện modifier của block
.block__element--modifier: Thể hiện modifier của element trong block
# Tính ứng dụng
- Xây dựng bố cục layout website
- Xây dựng thành phần Website
# Ưu điểm
- Tái sử dụng dễ dàng
- Tính rõ ràng
- Giúp cả team làm việc với nhau dễ dàng
- Tính module, Không lo bị chồng class
# Nhược điểm
- Tên Class bị dài
# Khi nào sử dụng BEM
- Dự án nhiều members
- Dự án lớn, số lượng nhiều page nhiều thành phần trên một giao diện