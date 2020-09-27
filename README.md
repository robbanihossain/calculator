# calculator<!doctype html>
<html>
<head>
	<title>Calculator Design</title>
	<link rel="stylesheet" href="style.css">
</head>

<body>
	<div class="container">
		<h3>Calculator </h3>
		<input type="text" name="text">
		<button class="btn1">C</button>
		<button class="btn1">+/-</button>
		<button class="btn1">%</button>
		<button class="btn2">/</button>
		<button class="btn1">7</button>
		<button class="btn1">8</button>
		<button class="btn1">9</button>
		<button class="btn2">☓</button>
		<button class="btn1">4</button>
		<button class="btn1">5</button>
		<button class="btn1">6</button>
		<button class="btn2">—</button>
		<button class="btn1">1</button>
		<button class="btn1">2</button>
		<button class="btn1">3</button>
		<button class="btn2">÷</button>
		<button class="btn1">0</button>
		<button class="btn1">.</button>
		<button class="btn1">DEL</button>
		<button class="btn3">=</button>


	</div>


	
</body>
</html>
h3{
	text-align: center;
	color: black;
}
input{
	width: 193px;
	height: 25px;
	border: solid 1px orange;
	box-shadow: 1px 1px 2px orange;
	
}
.container{
	margin: 0 auto;
	box-shadow: 1px 1px 2px black;
	border: double 2px black;
	width: 200px;
	padding: 10px;
}
.btn1{
	margin-top: 2px;
	padding: 3px;
	height: 46px;
	width: 46px;
	color: white;
	background-color: black;
	border: none;
}
.btn2{
	margin-top: 2px;
	padding: 3px;
	height: 46px;
	width: 46px;
	color: white;
	background-color: #9342f5;
	border: none;
}
.btn3{
	margin-top: 2px;
	padding: 3px;
	height: 46px;
	width: 46px;
	color: white;
	background-color: orange;
	border: none;
}
.btn1:hover{
	margin-top: 2px;
	padding: 3px;
	height: 46px;
	width: 46px;
	color: white;
	background-color: #f59942;
	border: none;
}
.btn2:hover{
	margin-top: 2px;
	padding: 3px;
	height: 46px;
	width: 46px;
	color: white;
	background-color: #f59942;
	border: none;
}
.btn3:hover{
	margin-top: 2px;
	padding: 3px;
	height: 46px;
	width: 46px;
	color: white;
	background-color: #42f572;
	border: none;
}
