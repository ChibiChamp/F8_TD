# Các thẻ phổ biến trong HTML

## Thẻ block và thẻ inline

1. Thẻ block

- Chiều rộng mặc định tỷ lệ 100% so với chiều rộng của thẻ cha (Thẻ chứa nó)
- Luôn ở 1 hàng mới
- Chứa được các thẻ block và inline khác

2. Thẻ inline

- Chiều rộng mặc định theo nội dung
- Các thẻ inline đứng cạnh nhau nằm trên 1 hàng
- Không bọc được thẻ block

## Các thẻ html trong nhóm block

1. Thẻ heading (Thẻ tiêu đề)

```html
<h1>Tiêu đề trang web</h1>
<h2>Tiêu đề trang web</h2>
<h3>Tiêu đề trang web</h3>
<h4>Tiêu đề trang web</h4>
<h5>Tiêu đề trang web</h5>
<h6>Tiêu đề trang web</h6>
```

- Các thẻ heading phải nối tiếp nhau

2. Thẻ Văn bản (P)

```html
<p>Văn Bản</p>
<p>Văn Bản</p>
<p>Văn Bản</p>
<p>Văn Bản</p>
```

3. Thẻ định dạng danh sách
   3.1. Định danh danh sách

```html
<ul>
  <li>Danh sách 1</li>
  <li>Danh sách 2</li>
  <li>Danh sách 3</li>
  <li>Danh sách 4</li>
  <li>Danh sách 5</li>
</ul>
```

3.2.Định dạng danh sách theo thứ tự

```html
<ol>
  <li>Danh sách 1</li>
  <li>Danh sách 2</li>
  <li>Danh sách 3</li>
  <li>Danh sách 4</li>
  <li>Danh sách 5</li>
</ol>
```

4. Thẻ phân chia nội dung (div)

- nhóm các thẻ html khác thành 1 khu vực
- Phân chia bố cục trang web

**Lưu ý**

- không thay đổi định dạng ban đầu của các văn bản, các thẻ html khác
- Dùng nhiều trong bố cục trang (Layout)

5. Thẻ trích dẫn (blockquote)

```html
<blockquote>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos.
  </p>
</blockquote>
```

6. Thẻ hr

```html
<hr />
```

- Tạo đường kẻ ngang

7. Các thẻ thay thế thẻ div

- header: Thẻ hiện phần đầu trang web hoặc phần đầu card
- footer: Thể hiện cuối của trang web hoặc chân của 1 card item
- nav: Thể hiện thanh điều hướng (menu)
- main: Phần thân của trang web (Sau header và trước footer)
- section: Thể hiện 1 phần trên 1 trang web
- article: Thể hiện 1 nội dung độc lập với các phần còn lại (Vd: sản phẩm, bài viết, bình luận,..)
- aside: Thể hiện cột bên của trang web
