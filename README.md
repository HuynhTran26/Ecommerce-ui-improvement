1. Giới thiệu
Bài tập thực hiện khảo sát giao diện website thương mại điện tử JUNO và
xây dựng một phương án cải tiến giao diện tìm kiếm sản phẩm bằng HTML5
và CSS3. Nội dung gồm khảo sát các khu vực mua sắm chính, sử dụng AI hỗ
trợ phân tích, đối chiếu kết quả AI với giao diện thực tế và tự điều
chỉnh mã nguồn.
2. Website tham khảo
- Tên website: JUNO
- URL: https://juno.vn/
- Nhóm sản phẩm kinh doanh: Giày dép; túi và ví; phụ kiện thời
  trang; quần áo; sản phẩm làm đẹp.
- Khách hàng mục tiêu: Phụ nữ Việt Nam có nhu cầu mua sắm giày
  dép, túi xách, sản phẩm thời trang và làm đẹp.
- Các khu vực đã khảo sát: Trang chủ, danh mục sản phẩm, chi tiết
  sản phẩm, tìm kiếm và giỏ hàng.
- Khu vực được lựa chọn để cải tiến: Tìm kiếm sản phẩm.
3. Chức năng
Giao diện minh họa được xây dựng có các thành phần:
- Hiển thị ô tìm kiếm và từ khóa tìm kiếm.
- Hiển thị danh sách sản phẩm minh họa.
- Hiển thị hình ảnh, tên và giá sản phẩm.
- Cung cấp liên kết xem thêm kết quả.
- Điều chỉnh bố cục theo kích thước màn hình máy tính và điện thoại.
Lưu ý: Đây là giao diện minh họa bằng HTML/CSS. Chức năng tìm kiếm
chưa kết nối với cơ sở dữ liệu hoặc hệ thống sản phẩm thực tế; dữ liệu
và hình ảnh trong giao diện có thể chỉ mang tính minh họa.
4. Công nghệ
- HTML5
- CSS3
- Google Chrome DevTools để kiểm tra giao diện ở các kích thước màn
  hình khác nhau.
5. Cách chạy
1. Tải mã nguồn về máy tính và giải nén nếu mã nguồn nằm trong file
   ZIP.
2. Đặt index.html và style.css trong cùng thư mục theo cấu trúc dự
   án.
3. Mở file index.html bằng trình duyệt web như Google Chrome.
4. Kiểm tra giao diện trên máy tính và sử dụng Chrome DevTools để mô
   phỏng kích thước màn hình điện thoại.
6. Cải tiến đã thực hiện
Qua khảo sát khu vực tìm kiếm trên website JUNO, khi nhập từ khóa "túi",
website hiển thị các gợi ý sản phẩm kèm hình ảnh, tên và thông tin giá.
Khung gợi ý có thể chiếm nhiều diện tích hiển thị, đặc biệt trên màn
hình điện thoại. Đây là nhận định về khả năng phát sinh vấn đề trải
nghiệm người dùng, không phải kết luận rằng mọi người dùng đều gặp lỗi.

Phương án cải tiến tập trung vào việc trình bày ô tìm kiếm rõ ràng, sắp
xếp danh sách gợi ý dễ quan sát, hiển thị hình ảnh cùng tên và giá sản
phẩm, đồng thời cung cấp liên kết xem thêm kết quả. CSS được tổ chức để
hỗ trợ bố cục responsive.

Trong quá trình kiểm tra mã nguồn, tôi phát hiện hình ảnh của hai sản
phẩm sử dụng cùng một đường dẫn. Em đã chỉnh sửa thuộc tính src của
thẻ <img> ở sản phẩm thứ hai để sử dụng một đường dẫn ảnh riêng. Sau
khi chỉnh sửa, cần kiểm tra trên trình duyệt để xác nhận hình ảnh tải
thành công, phù hợp với sản phẩm và không bị méo hoặc cắt mất phần quan
trọng.
7. Hỗ trợ từ AI
AI được sử dụng để hỗ trợ phân tích năm khu vực trên website JUNO gồm
Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm và Giỏ hàng;
xác định mục đích, thành phần giao diện, điểm thuận tiện, vấn đề UX có
thể phát sinh và đề xuất cải tiến. AI cũng hỗ trợ đề xuất bố cục tìm
kiếm, giải thích vai trò của HTML/CSS và hỗ trợ xây dựng mã nguồn giao
diện minh họa.

Em đã đối chiếu nội dung AI với giao diện website được khảo sát, giữ
lại thông tin có căn cứ, điều chỉnh những nhận xét còn mang tính suy
đoán và bổ sung đánh giá cá nhân. Tôi cũng tự phát hiện và chỉnh sửa
đường dẫn ảnh bị trùng trong index.html.

Các đề xuất như tối ưu khung gợi ý hoặc thay đổi bố cục trên điện thoại
cần được kiểm tra thực tế trên nhiều kích thước màn hình trước khi kết
luận hiệu quả. AI là công cụ hỗ trợ; người thực hiện chịu trách nhiệm
kiểm tra thông tin, hiểu mã nguồn và đánh giá kết quả.
