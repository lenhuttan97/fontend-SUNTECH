1. Tại sao sử dụng HTML
2. Cách tạo trang HTML & Cấu trúc của 1 trang HTML
3. Cấu trúc và qui tắc của thẻ HTML
- Thông thường thẻ HTML sẽ có thẻ đóng và thẻ mở
- Thẻ HTML có tên giống nhau ở thẻ đóng mở, chỉ khác nhau ở dấu /
- Trường hợp đặc biệt thì sẽ không có thẻ đóng, nhưng có đóng thẻ trên chính nó
- Thẻ html có thể không có, có 1 hoặc nhiều thuộc tính

	<tagName attribute1="value1" attribute2="value2" ....>Nội dung</tagName>
	hoặc
	<tagName attribute1="value1" attribute2="value2" .... />

- Nội dung bọc giữa thẻ đóng và mở: Text, Ảnh, Video, Các thẻ HTML...
- Có thể tự định nghĩa thẻ HTML

4. Các thẻ HTML thường
4.1. Nhóm các thẻ tiêu đề (nội dung)
	- Danh sách các thẻ từ h1 đến h6

	<h1>Nội dung</h1>
	<h2>Nội dung</h2>
	<h3>Nội dung</h3>
	<h4>Nội dung</h4>
	<h5>Nội dung</h5>
	<h6>Nội dung</h6>

4.2 Tiêu đề của trang
- <title>Nội dung tiêu đề</title>
SEO: Quan trọng

4.3. Các thẻ thể hiện văn bản
- <p>Nội dung</p>
	Thể hiện đoạn văn bản
- <br/>: Xuống dòng
- <u>Nội dung</u>: Gạch chân văn bản
- <del>Nội dung</del>: Xóa văn bản
- <i>Nội dung</i>: In nghiêng
- <font size="12" color="red">Nội dung</font>
- <b>Nội dung</b> & <strong>Nội dung</strong>
	(dùng để in đậm văn bản)
	SEO: strong tốt hơn

- Thể hiện danh sách (tuần tự & bất tuần tự)
	<ul>
		<li>Nội dung</li>
		<li>Nội dung</li>
		<li>Nội dung</li>
	</ul>

	<ol>
		<li>Nội dung</li>
		<li>Nội dung</li>
		<li>Nội dung</li>
	</ol>

- Thẻ <pre>Nội dung</pre>

4.4. Thẻ liên kết
	<a href="#" target="">Nội dung</a>

	href:
		- Liên kết đến
		- Mặc định là #

	target: Qui định, cách mở trang
		+ __blank: mở tab mới

4.5. Thẻ thể hiện hình ảnh
	<img src="" alt="" width="" height="" />

	src: Đường dẫn của ảnh
	alt: Mô tả cho ảnh
	width: chiều rộng
	height: chiều cao

4.6. Các loại thẻ HTML
Có 3 loại thẻ HTML
	- Block: <div>Nội dung</div>
	- Inline: <span>Nội dung</span>
	- None: <meta charset="utf-8" />

5. Thẻ Table
	<table align="" width="" border="" cellpadding="" cellspacing="">
		<tr align="" width="">
			<td align="" width="" valign="">1</td>
			<td>1</td>
			<td>1</td>
			<td>1</td>
		</tr>
		<tr>
			<td>1</td>
			<td>1</td>
			<td>1</td>
			<td>1</td>
		</tr>
		<tr>
			<td>1</td>
			<td>1</td>
			<td>1</td>
			<td>1</td>
		</tr>
	</table>

	Thuộc tính dùng chung cho table, tr và td
	+ width: Qui định độ rộng của trang
	+ align: (left|right|center) canh lề table so với trình duyệt
	+ border: Qui định đường viền
	+ bgcolor: Qui định màu nền

	Thuộc tính cho td
		valign: (top|midlle|bottom) Canh nội dung trong cột theo chiều dọc

	* Gộp dòng và gộp cột trong table
		