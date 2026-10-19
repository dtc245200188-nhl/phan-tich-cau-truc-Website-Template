# Phân tích cấu trúc website: VnExpress (vnexpress.net)

## 1. Phân tích các phần của trang

**Header** – Nằm trên cùng của trang, chứa logo/tên báo VnExpress. Đây là phần giúp người đọc nhận ra thương hiệu ngay khi vào trang.

**Navigation Menu** – Là một thanh ngang nằm ngay dưới header, gồm các chuyên mục như Thời sự, Thế giới, Kinh doanh, Giải trí, Thể thao, Pháp luật, Giáo dục... Các mục xếp thành một hàng ngang để người đọc chuyển nhanh giữa các chuyên mục.

**Content Section** – Là phần lớn nhất, chia làm hai cột. Cột trái (rộng hơn) là các tin mới và quan trọng: một tin nổi bật có ảnh lớn, bên dưới là danh sách các tin có tiêu đề và đoạn mô tả ngắn. Cột phải (hẹp hơn) là các mục phụ như tin xem nhiều và các chuyên mục chuyên sâu.

**Footer** – Nằm cuối trang, chứa thông tin bản quyền (© VnExpress.net), thông tin liên hệ tòa soạn và các liên kết phụ.

## 2. Cách các phần được bố trí

Trang đi theo thứ tự từ trên xuống: Header → Navigation Menu → Content (2 cột) → Footer. Các phần đều được căn giữa trong một khung có chiều rộng cố định, hai bên là khoảng trắng. Thanh menu dùng bố cục hàng ngang, còn phần nội dung chia cột để tin chính nằm bên trái và thông tin bổ trợ nằm bên phải.

## 3. Bố cục đã dựng lại bằng HTML & CSS

- `index.html`: dùng các thẻ `header`, `nav`, `main` (gồm `section` + `aside`), `footer`.
- `style.css`: Flexbox cho thanh menu, CSS Grid (`2fr 1fr`) cho 2 cột nội dung, media query chuyển về 1 cột trên màn hình nhỏ.
- Ảnh được thay bằng các khung xám giữ chỗ vì đề chỉ yêu cầu tập trung vào bố cục.
