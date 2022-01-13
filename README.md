# The-jQuery-button-controls-the-left-and-right-scrolling-code
The jQuery button controls the left and right scrolling code
*{margin:0;padding:0;}
body {
	margin:0px;
	padding:0px;
	font-size:12px;
	font-family:"微软雅黑";
}
.scrollpic {
	width: 1100px;
	margin:40px auto 0 auto;
}
#myscroll {
	display: block;
	width: 100%;
	position: relative;
	height: 240px;
	overflow: hidden;
}
#myscroll #myscrollbox {
	display: block;
	float: left;
	position: absolute;
	left: 0;
	top: 0;
	width: 1000000px;
}
#myscroll ul {
	display: block;
	float: left;
	list-style-type: none;
	padding: 0;
	margin: 0;
}
#myscroll ul li {
	display: block;
	float: left;
	padding: 0;
	width:280px;
}
#myscroll ul li a {
	display: block;
	float: left;
	width: 260px;
	padding: 0;
	position: relative;
	height: 240px;
	color: #333;
}
#myscroll a .intro {
	position: absolute;
	left: 0;
	z-index: 10;
	background-color: #0057c4;
	filter: alpha(opacity=70);
	width: 260px;
	color: #fff;
	-moz-opacity: 0.7;
	-khtml-opacity: 0.7;
	opacity: 0.7;
	text-align: center;
}
#myscroll a .intro h5 {
	padding: 0;
	margin: 0;
	font-size: 16px;
	height: 40px;
	width: 260px;
	line-height: 30px;
	border-bottom: 1px solid #347fdc;
	font-weight:100;
}
#myscroll a .intro p {
	font-size: 13px;
	line-height: 20px;
	margin: 65px 70px;
	height: 70px;
	overflow: hidden;
}
#myscroll a .intro {
	bottom: -211px;
}
#myscroll a:hover .intro {
	bottom: 0px;
}
#mybtns {
	margin: 10px 0;
	width: 1100px;
	display: block;
	height: 42px;
}
#mybtns a {
	width: 42px;
	height: 42px;
	display: block;
	float: right;
	margin-right: 1px;
	background-color: #c1c1c1;
	margin-left:10px;
}
#mybtns a:hover {
	background-color: #347fdc;
}
#mybtns a:hover, #myscroll, #mybtns a, #myscroll a:hover .intro, #myscroll a .intro, #myscroll #myscrollbox {
	-webkit-transition: all 0.5s ease;
	-moz-transition: all 0.5s ease;
	-ms-transition: all 0.5s ease;
	-o-transition: all 0.5s ease;
	transition: all 0.5s ease;
}
#mybtns #left {
	background-image: url(../images/jt_l.png);
}
#mybtns #right {
	background-image: url(../images/jt_r.png);
}

#kinMaxShow {
	visibility: hidden;
	width: 100%;
	height: 500px;
	overflow: hidden;
}
