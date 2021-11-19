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
--