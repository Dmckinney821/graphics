# graphics
file:///Users/danielmckinney/Desktop/08/03_bg_ex/bg_images.html
/* reset browser styles */
html, body, div, span, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp,small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	vertical-align: baseline;
}
article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1.2;
}
ol { 
	padding-left: 1.4em;
	list-style: decimal;
}
ul {
	padding-left: 1.4em;
	list-style: square;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
} 
/* end reset browser styles */

.wrapper {
	width: 960px;
	margin-right: auto;
	margin-left: auto;
    overflow: hidden; /* contain float */
}

.main {
	float: right;
	width: 565px;
	margin-right: 15px;
	padding-top: 25px;
}

.announcement {
	margin-right: 600px;
	margin-left: 20px;
	
}

.copyright {
	clear: both;
	font: bold 12px Tahoma, Geneva, sans-serif;
	color: #65747E;
	padding: 5px;
  margin: 0 15px;
	border: 1px dotted #98AFBE;
  border-left: none;
  border-right: none;
}


.banner h1 {
	font: normal 48px Georgia, "Times New Roman", Times, serif;
	text-align: right;
  color: #272D32;
}

.main h2 {
	font: 24px Tahoma, Geneva, sans-serif;
	margin-bottom: 15px;
	font-family: Tahoma, Geneva, sans-serif;
}
.main p {
	font: 14px Tahoma, Geneva, sans-serif;
	color: #323A3F;
	margin-bottom: 20px;
	font-family: Tahoma, Geneva, sans-serif;
}

.announcement h2 {
	font: italic bold normal 20px Georgia, "Times New Roman", Times, serif;
	text-align: center;
	color: #323A3F;
	text-transform: uppercase;
	letter-spacing: 1px;
	margin-bottom: 18px;
}
.announcement ul {
	font: 14px Tahoma, Geneva, sans-serif;
}

/* add your styles here */

html {
	height: 100%;
	background-image: linear-gradient(to bottom, rgb(176,194,213), white 700px);
}
.wrapper {
	background-color: #FFF;
	background-image: url(images/bg_main.jpg);
	background-position: left top;
	background-repeat: no-repeat;
}
.banner {
	margin-top: 48px;
}
.announcement {
	background: url(images/scroll_top.jpg) no-repeat center top,
	url(images/scroll_bottom.jpg) no-repeat center bottom,
	url(images/scroll_middle.jpg) repeat-y center top;
	padding: 70px 0 60px 0;
	margin-top:115px;
}
.main h2 {
	background-image: url(images/underline.png);
	background-repeat: no-repeat;
	background-position: left bottom;
	padding-bottom: 7px;
}
.announcement li {
	list-style: none;
	background-image: url(images/bullet.png);
	background-repeat: no-repeat;
	background-position: 0 4px;
	padding-left: 25px;
	margin-bottom: 10px;
	margin-left: 30px;
	margin-right:40px;
}





<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>Background Images</title>
<link href="styles.css" rel="stylesheet">
<style>

</style>
</head>
<body>
<div class="wrapper">
<div class="banner">
<h1>CSS: The Missing Manual</h1>
</div>
<div class="main">
<h2>Lorem Ipsum Dolor Sat</h2>
<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. </p>
<p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? </p>
<p>Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
<h2>Nisi Ut Aliquid</h2>
<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. </p>
<p>Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
</div>
<div class="announcement">
<h2>Announcements</h2>
<ul>
<li>Lorem Ipsum Dolor Sat</li>
<li>Quis nostrum exercitationem ullam</li>
<li>Eius modi tempora incidunt</li>
<li>Quis autem vel eum iure reprehenderit</li>
<li> Sed quia non numquam eius modi tempora incidu</li>
<li>Nemo enim ipsam voluptate</li>

</ul>
</div>
<div class="copyright">
<p>Copyright 2015, Lorem Ipsum Corporation</p>
</div>
</div>
</body>
</html>
