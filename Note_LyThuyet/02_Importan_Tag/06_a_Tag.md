# Thẻ a (anchor, liên kết hyperlink)
ví dụ:
```html
<a href="https://www.w3schools.com">Visit W3Schools.com!</a>
```
## Cách liên kết với google
điền vào ô tìm kiếm: (dùng %20 để thay thế khoảng trắng ghi khoảng trắng cũng đc, nó tự mã hóa lại hoạc dùng +)
```html
<a href="https://www.google.com.vn/?q=hoc%20html"></a>
```
tìm kếm luôn:
```html
<a href="https://www.google.com.vn/search?q=hoc%20html"></a>
```
## Lưu ý dùng thẻ a:
- chú ý href: nếu không có href thì thẻ a sẽ không hoạt động
- href không phải herf
- href="#": trở về đầu trang

## Phương thức tel, mailto
- Ngoài việc liên kết với trang web, thẻ a còn có thể liên kết với số điện thoại, email
```html
    <a href="tel:0123456789">sdt: 0123456789</a>
    <a href="tel: +84123456789">sdt: +84123456789</a>
    <a href="mailto:demo.gmail.com">email: demo.gmail.com</a>
```
bản chất chỉ đơn giản là đều hướng đến trình duyệt mở ứng dụng điện thoại hoặc email mặc định
### phân biệt to, cc, bcc
- cc: carbon copy, gửi cho người khác biết danh sách người nhận giống với mình
- bcc: blind carbon copy, gửi cho người khác nhưng không biết gồm những ai được nhận như mình
### Cách nhận sẵn các nội dung cho mail
- ? phân tách mailto và tham số, & phân tách các tham số
```html
    <a href="mailto:demo.gmail.com?cc=examble.gmail.com&bcc=examble.gmail.com&subject=subject&body=body">email: demo.gmail.com</a>
```

# Kết hợp menu, mục lục
