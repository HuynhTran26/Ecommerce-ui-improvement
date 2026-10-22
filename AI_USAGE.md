1. Công cụ AI

Tên công cụ: ChatGPT (OpenAI)

Mục đích: Hỗ trợ khảo sát, phân tích giao diện website thương mại điện tử, đề xuất phương án cải tiến và xây dựng mã nguồn HTML/CSS minh họa.

2. Mục đích sử dụng

Em sử dụng AI để hỗ trợ thực hiện các nội dung sau:

Phân tích giao diện website JUNO tại năm khu vực: Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm và Giỏ hàng.

Xác định mục đích, thành phần giao diện, điểm thuận tiện và những vấn đề trải nghiệm người dùng có thể phát sinh.

Đề xuất phương án cải tiến khu vực tìm kiếm sản phẩm.

Giải thích vai trò của các thành phần HTML và thuộc tính CSS được sử dụng.

Hỗ trợ xây dựng, kiểm tra và điều chỉnh mã nguồn giao diện minh họa.

3. Prompt đã sử dụng

Prompt 1: Phân tích giao diện website

Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng cho website thương mại điện tử.

Tôi đang khảo sát website JUNO (https://juno.vn/).

Hãy giúp tôi lập bảng phân tích các khu vực:

Trang chủ.

Danh mục sản phẩm.

Chi tiết sản phẩm.

Tìm kiếm.

Giỏ hàng.

Với mỗi khu vực, hãy nêu:

Mục đích của chức năng.

Thành phần giao diện cần có.

Điểm thuận tiện đối với khách hàng.

Một vấn đề có thể phát sinh.

Một đề xuất cải tiến.

Không khẳng định những tính năng chưa được kiểm chứng. Phân biệt rõ nhận xét dựa trên quan sát và đề xuất của AI.

Prompt 2: Đề xuất cải tiến giao diện tìm kiếm

Dựa trên kết quả khảo sát website JUNO, hãy đề xuất cải tiến khu vực tìm kiếm sản phẩm. Khi khách hàng nhập từ khóa “túi”, giao diện cần hiển thị ô tìm kiếm, danh sách sản phẩm gợi ý gồm hình ảnh, tên và giá, cùng liên kết xem tất cả kết quả. Hãy trình bày bố cục phù hợp cho máy tính và điện thoại, đồng thời giải thích các thành phần HTML/CSS cần sử dụng.

Prompt 3: Hỗ trợ xây dựng mã nguồn HTML/CSS

Hãy tạo giao diện minh họa khu vực tìm kiếm sản phẩm bằng HTML5 và CSS3. Giao diện cần có ô tìm kiếm, danh sách sản phẩm gồm hình ảnh, tên và giá, liên kết xem thêm kết quả và bố cục responsive. Mã nguồn cần dễ đọc, có thể chạy bằng cách mở file index.html trên trình duyệt và không yêu cầu framework.

Prompt 4: Kiểm tra và điều chỉnh mã nguồn

Hãy hướng dẫn kiểm tra giao diện tìm kiếm sản phẩm sau khi xây dựng bằng HTML/CSS. Giải thích cách kiểm tra hình ảnh, bố cục trên điện thoại và máy tính, đồng thời nêu vai trò của thuộc tính src, alt trong thẻ <img> và thuộc tính object-fit: cover trong CSS.

4. Kết quả AI đề xuất

AI hỗ trợ phân tích năm khu vực chính trên website JUNO, chỉ ra mục đích sử dụng, các thành phần giao diện, điểm thuận tiện, vấn đề UX có thể phát sinh và hướng cải tiến.

Đối với khu vực tìm kiếm, AI đề xuất bố cục gồm ba phần chính:

Ô tìm kiếm: Đặt ở vị trí dễ nhận biết, cho phép người dùng nhập từ khóa.

Danh sách gợi ý sản phẩm: Hiển thị hình ảnh, tên và giá sản phẩm để người dùng dễ quan sát.

Liên kết xem tất cả kết quả: Đặt bên dưới danh sách gợi ý để hỗ trợ điều hướng.

AI cũng hỗ trợ xây dựng mã nguồn HTML/CSS, sử dụng CSS Grid và các quy tắc responsive để điều chỉnh bố cục theo kích thước màn hình. Ngoài ra, AI giải thích vai trò của các thành phần HTML như <header>, <form>, <input>, <section>, <article>, <img> và <a>.

5. Kiểm tra và điều chỉnh

Sau khi đối chiếu kết quả AI với giao diện website JUNO đã khảo sát, em giữ lại các nhận xét có căn cứ, điều chỉnh những nội dung mang tính suy đoán và bổ sung đánh giá cá nhân. Những vấn đề UX được xem là khả năng có thể phát sinh, không được khẳng định là lỗi đã được kiểm chứng.

Trong quá trình kiểm tra mã nguồn, em phát hiện hình ảnh của sản phẩm thứ nhất và thứ hai sử dụng cùng một đường dẫn. Em đã chỉnh sửa thuộc tính src của thẻ <img> trong file index.html để sản phẩm thứ hai sử dụng một đường dẫn hình ảnh riêng.

Em cần kiểm tra lại trên trình duyệt để xác nhận hình ảnh tải thành công, hiển thị phù hợp và không bị méo hoặc cắt mất phần quan trọng. Em cũng có thể sử dụng Chrome DevTools để kiểm tra bố cục ở nhiều kích thước màn hình.

Giao diện hiện tại là bản minh họa bằng HTML/CSS, chưa kết nối cơ sở dữ liệu hoặc chức năng tìm kiếm sản phẩm thực tế. Vì vậy, em không xem đây là một website thương mại điện tử hoàn chỉnh.

6. Phần em hiểu và có thể giải thích

Qua quá trình thực hiện, em tìm hiểu và có thể giải thích vai trò của các thành phần mã nguồn quan trọng:

<header>: Chứa phần đầu giao diện, trong đó có thể đặt khu vực tìm kiếm.

<form>: Nhóm các thành phần nhập và gửi thông tin tìm kiếm.

<label>: Cung cấp nhãn cho ô nhập, giúp người dùng hiểu mục đích của trường thông tin.

<input type="search">: Cho phép người dùng nhập từ khóa tìm kiếm.

<button>: Tạo nút thực hiện thao tác, chẳng hạn nút tìm kiếm.

<section>: Gom nhóm nội dung gợi ý sản phẩm.

<article>: Đại diện cho một sản phẩm trong danh sách.

<img>: Hiển thị hình ảnh; thuộc tính src xác định đường dẫn ảnh và alt cung cấp nội dung mô tả thay thế.

<a>: Tạo liên kết đến sản phẩm hoặc trang kết quả.

CSS Grid và Flexbox: Hỗ trợ sắp xếp các thành phần theo hàng, cột và khoảng cách phù hợp.

Media queries: Cho phép thay đổi kiểu hiển thị theo kích thước màn hình.

object-fit: cover: Giúp ảnh lấp đầy khung mà vẫn giữ tỷ lệ, nhưng có thể cắt một phần hình ảnh.

Em hiểu rằng HTML đảm nhiệm cấu trúc nội dung, còn CSS định dạng và bố trí giao diện. Việc sử dụng AI giúp em tham khảo phương án triển khai nhanh hơn, nhưng em vẫn cần đọc mã nguồn, kiểm tra kết quả thực tế và tự giải thích được những thành phần đã sử dụng.