# AI Usage Log
## 1. Công cụ AI
Tên công cụ: ChatGPT

## 2. Mục đích sử dụng
- Phân tích giao diện và chức năng website Shopee.
- Đề xuất bố cục cải tiến cho khu vực tìm kiếm.
- Tạo mã nguồn HTML/CSS ban đầu cho giao diện.
- Hỗ trợ giải thích và sửa mã khi thêm thanh điều hướng.

## 3. Prompt đã sử dụng
_1/ Phân tích giao diện và chức năng website:_
Tôi đang khảo sát website: https://shopee.vn/
Hãy giúp tôi lập bảng phân tích các khu vực:
1. Trang chủ.
2. Danh mục sản phẩm.
3. Chi tiết sản phẩm.
4. Tìm kiếm.
5. Giỏ hàng.
Với mỗi khu vực, hãy nêu:
- Mục đích của chức năng.
- Thành phần giao diện cần có.
- Điểm thuận tiện đối với khách hàng.
- Một vấn đề có thể phát sinh.
- Một đề xuất cải tiến.
Không khẳng định những tính năng chưa được kiểm chứng.
Phân biệt rõ nhận xét dựa trên quan sát và đề xuất của AI.

_2/ Nhờ AI đề xuất giao diện cải tiến:_
Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử
bằng HTML5 và CSS3.
Tôi muốn cải tiến khu vực: [Tìm kiếm] của shopee.vn  thanh tìm kiếm khi khách hàng nhập từ khóa quá chung chung, viết sai chính tả hoặc chưa xác định chính xác tên sản phẩm, việc tìm được kết quả phù hợp có thể mất nhiều thời gian. Khách hàng có thể phải thay đổi từ khóa hoặc sử dụng thêm bộ lọc để thu hẹp kết quả tìm kiếm. Vì vậy, em sẽ cải tiến khu vực tìm kiếm bằng cách bổ sung gợi ý từ khóa phù hợp, hỗ trợ xử lý lỗi chính tả và bố trí các bộ lọc như giá bán, thương hiệu và đánh giá một cách dễ nhận biết hơn. 
Đối tượng sử dụng: khách hàng mua sắm trực tuyến tại Việt Nam.
Hãy đề xuất:
1. Bố cục giao diện.
2. Các thành phần HTML cần sử dụng.
3. Cách tổ chức CSS.
4. Cách hiển thị trên máy tính và điện thoại.
5. Những điểm cần kiểm tra về khả năng sử dụng.
Trước tiên, hãy giải thích phương án thiết kế.
Chưa tạo toàn bộ mã nguồn cho đến khi tôi yêu cầu.

_3/ AI hỗ trợ tạo mã HTML5 và CSS3 cho giao diện trang Mua sắm nhanh:_
Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện
thương mại điện tử bằng HTML5 và CSS3. Có các hình ảnh sản phẩm và tham khảo các trang web tmdt khác như shopee.vn hay tiki.vn hay lazada
Yêu cầu:
- Giao diện có tiêu đề và khu vực sản phẩm.
- Có tối thiểu 4 sản phẩm mẫu.
- Mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác.
- Bố cục phù hợp với màn hình máy tính và điện thoại.
- Mã HTML có cấu trúc rõ ràng.
- CSS được tách thành file riêng.
- Không sử dụng backend hoặc cơ sở dữ liệu.
- Không đưa thư viện hoặc thành phần không cần thiết vào dự án.
Giải thích cách chạy trang web và những phần tôi cần kiểm tra.

## 4. Kết quả AI đề xuất
Đối với yêu cầu 1/, AI lập bảng phân tích 5 khu vực của Shopee và đưa ra ba hướng cải tiến chính: Giảm quá tải thông tin, sửa lỗi khi tìm kiếm để thuận tiện và nhanh chóng hơn và sửa phần giao diện khi bỏ và giỏ hàng/thanh toán để minh bạch giá cả hơn. Yêu cầu 2/, AI đề xuất cải tiến khu vực tìm kiếm: gợi ý từ khóa, hỗ trợ lỗi chính tả, bộ lọc giá bán, thương hiệu, đánh giá. Yêu cầu 3/, dựa vào những đề xuất AI đưa ra ở yêu cầu 2/ đã tạo thử một trang giao diện với khu vực tìm kiếm tối ưu hơn.

## 5. Kiểm tra và điều chỉnh
- Đã kiểm tra: Sử dụng DevTools để xem giao diện ở kích thước điện thoại và máy tính
- Đã sử đổi/bổ sung:
  + Xóa các nút chức năng dư thừa phía dưới banner.
  + Thêm thanh điều hướng <nav class="top-nav">: Trang chủ, Video ngắn, Thông báo (huy hiệu 3, 3 thông báo mẫu), Tài khoản (Hồ sơ, Đơn mua, Yêu thích, Đăng nhập).
  + Thêm khu vực Video ngắn: 4 khung video dọc 9:16, có nút ▶, thời lượng, lượt xem.
  + Nhận xét cá nhân đối với phần đề xuất của AI cho yêu cầu 1/: giỏ hàng và danh mục sản phẩm của Shopee đã khá hoàn thiện, không đề xuất cải tiến.
  
## 6. Phần tôi hiểu và có thể giải thích
- <nav>, <ul>, <li>: vùng điều hướng và danh sách mục; trình đọc màn hình nhận ra đây là menu.
- <details>/<summary>: tạo menu thả xuống không cần JavaScript. Thuộc tính name="nav-menu" để mở mục này thì mục kia tự đóng.
  - position: sticky; top: 0: giữ thanh điều hướng cố định ở đầu màn hình khi cuộn. z-index: 30 đặt thanh điều hướng nằm trên header và các menu.
- scroll-padding-top: 60px trên html: chừa chỗ cho thanh điều hướng, nên tiêu đề không bị che khi bấm "Video ngắn" hay "Sản phẩm".
- aspect-ratio: 9 / 16: giữ khung video dọc ở mọi kích thước. Lưới video là 4 cột trên máy tính và 2 cột trên màn hình dưới 950px.
