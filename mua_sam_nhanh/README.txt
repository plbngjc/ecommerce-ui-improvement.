MUA SẮM NHANH - GIAO DIỆN THƯƠNG MẠI ĐIỆN TỬ MẪU

Tệp:
- index.html: cấu trúc HTML5.
- style.css: toàn bộ định dạng CSS3.

Cách chạy:
1. Giải nén thư mục.
2. Mở index.html bằng Chrome, Edge hoặc Firefox.
3. Cần kết nối Internet để tải ảnh minh họa từ images.unsplash.com.
4. Có thể mở bằng VS Code và dùng Live Server nếu muốn tự động tải lại khi sửa.

Lưu ý:
- Đây là giao diện tĩnh, không có backend/cơ sở dữ liệu.
- Danh sách gợi ý chỉ hiển thị khi thanh tìm kiếm được focus; đây là minh họa CSS, chưa có gợi ý động theo từng ký tự.
- Nút bộ lọc và nút thêm vào giỏ chỉ là thành phần giao diện, chưa thực hiện lọc hay thêm sản phẩm thật.
- Giá, đánh giá, lượt bán và nhãn ưu đãi là dữ liệu mẫu.
- Ảnh sản phẩm lấy từ URL ảnh Unsplash; nếu không có Internet hoặc URL ảnh thay đổi, ảnh có thể không hiển thị.

NHẬT KÝ CHỈNH SỬA (sau khi kiểm tra bằng trình duyệt)
1. Nút tìm kiếm trên điện thoại: biểu tượng bị mất (nút trống). Đã tách biểu tượng
   vào <span class="search-icon"> và chỉ ẩn <span class="search-text"> ở màn hình nhỏ.
2. Liên kết "Giỏ hàng" (#cart) trước đây cuộn nhầm tới khối "Chưa tìm thấy sản phẩm".
   Đã đổi id khối đó thành #search-help và thêm khu vực #cart đúng nghĩa.
3. Chữ trên điện thoại quá nhỏ (7-9px): nâng lên tối thiểu 10px; nút "Thêm vào giỏ"
   cao hơn (35px -> 43px) để dễ chạm.
4. Thẻ <img>: thêm width/height và loading="lazy" để giảm giật bố cục và tải nhanh hơn.

CẬP NHẬT LẦN 2: THANH ĐIỀU HƯỚNG
- Đã bỏ: thanh tiện ích đầu trang (Ưu đãi mỗi ngày / Sản phẩm / Hỗ trợ / Giao hàng toàn quốc)
  và hàng 3 thẻ lợi ích (Tìm kiếm nhanh / Dễ so sánh / Thiết kế linh hoạt).
- Đã thêm thanh điều hướng cố định trên cùng (<nav class="top-nav">): Trang chủ, Video ngắn,
  Thông báo (có số đếm), Tài khoản. Thông báo và Tài khoản dùng <details>/<summary>,
  không cần JavaScript; mở mục này thì mục kia tự đóng (thuộc tính name="nav-menu").
- Đã thêm khu vực "Video ngắn" (#video): 4 khung video dọc 9:16 minh họa, chưa phát video thật.
- html { scroll-padding-top } giúp tiêu đề không bị thanh điều hướng cố định che khi cuộn tới neo.
- Lưu ý: dòng "Trang chủ" luôn được tô sáng vì chưa dùng JavaScript để đổi theo vị trí cuộn.
