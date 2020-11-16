# DẪN LINK
- ## Thẻ <a> </a> định nghĩa một đường dẫn

VD: <a href="url">link text</a>
- `href` là thuộc tính quan trọng nhất của thẻ <a> </a>, chỉ ra đường dẫn
- `link test` là phần hiển thị cho người đọc
## Thuộc tính target
- `target` chỉ ra cửa số mới sẽ được mở thế nào

VD: <a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

_blank: mở cửa sổ mới khi ấn link

_self = _parent = _top: chuyển đến link trong cùng trang

- Dùng ảnh làm link. VD: <a href="https://www.w3schools.com/html/default.asp">
<img src="123.jpg" alt="HTML tutorial" style="width:42px;height:42px;"></a>

để thẻ <img> bên trong thẻ <a></a>

- Gửi thư: <a href="mailto:ccrazykart125@gmail.com"> send email</a>

dùng thẻ send email để gửi thư
- Link title. VD: <a href="https://www.w3schools.com/" title="go to w3schools" target="_blank">Visit w3schools.com</a>
- Nút nhấn là link. VD: <button onclick="document.location='default.asp'">HTML Tutorial</button>