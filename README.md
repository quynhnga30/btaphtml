# btaphtml
--lket html
<a href="url">link text</a>
vd
<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

--lket html sdung hanh lam lien ket
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

--lket 1 đia chi email
<a href="mailto:someone@example.com">Send email</a>

--nut duoi dang mot lket
<button onclick="document.location='default.asp'">HTML Tutorial</button>
--tieu de lket
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML
 section">Visit our HTML Tutorial</a>
 --1 url day du de lket trang web
 <a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>
 
 --lket 1 trang nam trong thu muc web
 <a href="/html/default.asp">HTML tutorial</a>
 --lket den 1 trang cung thu muc vs trang hien tai
 <a href="default.asp">HTML tutorial</a>



 --lket mau

 <style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
--cac nut lket
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>
--hinh anh
--Hình ảnh có thể cải thiện thiết kế và giao diện của một trang web.

<img src="pic_trulli.jpg" alt="Italian Trulli">

<img src="img_girl.jpg" alt="Girl in a jacket">

<img src="img_chania.jpg" alt="Flowers in Chania">

-bản đồ hình ảnh
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>
-hình nền
<div style="background-image: url('img_girl.jpg');">

<style>
div {
  background-image: url('img_girl.jpg');
}
</style>

-nền cho toàn bộ trang
<style>
body {
  background-image: url('img_girl.jpg');
}
</style>
-bối cảnh lặp lại
<style>
body {
  background-image: url('example_img_girl.jpg');
}
</style>
-tránh nền lặp lại
<style>
body {
  background-image: url('example_img_girl.jpg');
  background-repeat: no-repeat;
}
</style>
-bìa nền
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
</style>
-căng nền
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
--yếu tố hình ảnh
-hình ảnh và kích thước khác nhau
<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>
-định dạng hình ảnh đầu tiên
<picture>
  <source srcset="img_avatar.png">
  <source srcset="img_girl.jpg">
  <img src="img_beatles.gif" alt="Beatles" style="width:auto;">
</picture>

--thêm favicon
<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
--xác định một bảng html
-bảng đơn giản
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
-bảng thu gọn
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}

-bảng kiểu
table, th, td {
    border: 1px solid white;
    border-collapse: collapse;

}
th, td{
    background-color: #96D4D4;
}
-đường viền tròn
table, th, td {
  border: 1px solid black;
  border-radius: 10px;
}
-đường viền chấm
 th, td {
  border-style: dotted;
}
-màu viền
 th, td {
  border-color: #96D4D4;
}
--kích thước bảng
-chiều rộng
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
-chiều rộng cột
<table style="width:100%">
  <tr>
    <th style="width:70%">Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
-chiều cao
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr style="height:200px">
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
--tiêu đề bảng
-tiêu đề html
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
-bảng dọc
<table>
  <tr>
    <th>Firstname</th>
    <td>Jill</td>
    <td>Eve</td>
  </tr>
  <tr>
    <th>Lastname</th>
    <td>Smith</td>
    <td>Jackson</td>
  </tr>
  <tr>
    <th>Age</th>
    <td>94</td>
    <td>50</td>
  </tr>
</table>

-căn chỉnh tiêu đề
th {
  text-align: left;
}
-tiêu đề nhiều cột
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
-bảng chú thích
<table style="width:100%">
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>
--phần đệm và khoảng cách
-ô đệm
th, td {
  padding-top: 10px;
  padding-bottom: 20px;
  padding-left: 30px;
  padding-right: 40px;
}
-khoảng cách
table {
  border-spacing: 30px;
}
--html colspan và rowspan
-colspan
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>57</td>
  </tr>
</table>
-rowspan
<table>
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
</tr>
</table>

--danh sách html
-ko theo thứ tự
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
-theo thứ tự
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
-danh sách mô tả
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
-danh sách khác
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>

