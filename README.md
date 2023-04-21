<h1 align="center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="center">Лабораторная работа №7</p>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="right">Выполнил: Морошкин Максим Александрович</p>
<p align="right">Проверил: Соболев Е. И.</p>
<br>
<br>
<br>
<br>
<br>
<br>

<p align="center">г. Южно-Сахалинск <br> 2023 год</p>

<h2 align="center">Введение</h2>
<p align="justify">Лабораторная работа по созданию страницы по образцу.</p>

<h2>Цели и задачи</h2>
Повторить по образцу, то есть сделать такой же макет используя материалы из архива lab7.zip
![image](https://user-images.githubusercontent.com/128196268/230574478-3a53236a-c68f-4264-8257-be20cec8598d.png)

<h2>Решение задач</h2>

1)index.html
```html
<!DOCTYPE html>
<html>
<head>
	<title>Лабораторная 6</title>	
	<link rel="stylesheet" href="style.css">
</head>
<body>		
	<div class="header">
	
		<div class="logo">
			<p>Elysa4t</p>
		</div>
			
		<div class="navigation">
			<li><a href="#" style="background: #a2231d;border-radius: 5px;padding:10px">Home</a></li>
			<li><a href="#">Archives</a></li>
			<li><a href="#">Gallery</a></li>
			<li><a href="#">About</a></li>
			<li><a href="#">Contact</a></li>
		</div>
		
	</div>	

	<div class="banner">	
		<div class="banner-image">
			<img src="banner-image.jpg" alt="">
		</div>
			
		<div class="banner-text">
			<p>Magna sed phasellus consequat lorem ipsum dolor</p>
		</div>	
	</div>
	
	<div class="main-image">
		<div class="main-block">

			<div class="block1">
			
				<div class="block1-info">
					<p>Posted by <a href="">Someone</a> on April 14, 2012</p>
				</div>
				
				<h1>Lorem ipsum sed veroeros amet</h1>

				<div class="block1-image">
					<img src="block1-image.jpg" alt="">
				</div>
				
				<div class="block1-text">
					<p>
						Nam vestibulum hendrerit orci, sed pharetra elit elementum in. Donec in eros sed odio varius tempus. Vestibulum quis quam et velit rutrum ornare nec a massa. Curabitur malesuada ullamcorper nunc in suscipit. Donec semper venenatis dui sed facilisis. Morbi congue facilisis ante in feugiat. Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa ac odio ornare sodales. Nunc rhoncus vulputate nisi sed malesuada. Fusce ac mauris dui, id luctus ligula. Integer hendrerit.
					</p>
				</div>
				
				<div class="block1-comments">
					<p>Posted in <a href="#"> News,<a href="#"><a href="#"> Design,</a><a href="#"> Other</a></p>
					<p><a href="#">235 Comments</a></p>
				</div>
	
			</div>
			
			<div class="block2">
					
					<div class="block2-info">
						<p>About Elysa4t</p>
					</div>

					<div class="block2-text">
						<p>
							Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.
						</p>
					</div>

					<div class="block2-info"><p>Recent Post</p></div>

					<div class="block2-links">
						<ul>
							<li><a href="">Hendrerit orci sed pharetra elit</a></li>
							<li><a href="">Donec in eros odio varius tempus</a></li>
							<li><a href="">Vestibulum quis quam et velit</a></li>
							<li><a href="">Rutrum ornare nec sed curabitur</a></li>
							<li><a href="">Malesuada ullamcorper nunc</a></li>
						</ul>
					</div>

					<div class="block2-info"><p>Something Else</p></div>

					<div class="block2-text">
						<p>
							Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.
						</p>
					</div>
			</div>
			
		</div>
	</div>
	
	<div class="block3-image">
	
		<div class="block3">
			
			<div class="block3-text">
				<h1>Just another widget</h1>
				<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.<p>
			</div>

			<div class="block3-text">
				<h1>Just another widget</h1>
				<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
			</div>

			<div class="block3-text">
				<h1>Just another widget</h1>
				<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
			</div>
			
		</div>
	</div>
	
	<footer>
		
		<div class="footer-info">
			<p>&copy; Your Website Name | Elysa4T by <a href=""> 4Templates </a>| Photos by <a href=""> Fotogrph</a></p>
		</div>
		
	</footer>
	
</body>
</html>
```

2)CSS

```html
@import url('https://fonts.googleapis.com/css?family=Cookie');
@import url('https://fonts.googleapis.com/css?family=Arvo');
body {
	font-family: "Arvo", CURSIVE;
	font-size: 13px;
}

* {
	margin: 0;
	padding: 0;
}

.header {
	height: 187px;
	background: url("header.png");
	display: flex;
}

.logo {
	width: 200px;
	height: 100px;
	background: #a2231d;
	margin:auto;
	border-radius:10px;
}
.logo p {
	text-align:center;
	padding:15px;
	color: white;
	font-size: 60px;
	font-family: "Cookie", CURSIVE;	
}

.navigation li {
	list-style: none;
}


.navigation{
	display: flex;
	margin: auto;
}

.navigation a {
	font-size: 20px;
	color: white;
	margin-right:70px;
	text-decoration: none;
}

.navigation li a:hover{
	background: #a2231d;
	border-radius: 5px;
	padding:10px;
}


.banner {
	background: url("banner.png");
	display: flex;
	flex-direction: column;
}

.banner-image {
	margin-top:20px;
	text-align: center;	
	margin-bottom:-5px;
}

.banner-text {
	background: url("banner-text.png")no-repeat center;
	margin-bottom:20px;
}

.banner-text p{
	padding:15px;
	text-align: center;
	color: white;
	font-size:40px;
	font-family:"Cookie", cursive;
}	


.main-image {
	background: url("main-image.png");

}
.main-block {
	max-width: 960px;
	margin:auto;
	display: flex;
	padding: 30px;
	justify-content: space-around;
}

.block1 {
	background: white;
	max-width: 650px;
	padding: 20px;
	margin-right: 20px;
	border-radius: 5px;
}

.block1-info {
	background: url("block1-info.png") no-repeat;
	width:330px;
	height:38px;
	margin-left:-20px;
}

.block1-info p {
	text-align:center;
	padding:10px;
	font-size: 15px;
	font-family:serif;
	color: white;	
}

.block1-info a {
	font-size: 15px;
	font-family: serif;
	color: white;
}

.block1 h1 {
	padding: 10px;
	font-size: 40px;
	color: #4e2b22;
	font-family: serif;
	font-weight: 400;
}

.block1-image {
	margin: auto;
	max-width:580px;
}

.block1-image img {	
	border-radius: 5px;
}
.block1-text {
	padding: 10px;
}
.block1-text p {
	font-size: 15px;	
	line-height: 2;
	font-family:sans-serif;
	text-align:justify;
}
.block1-comments {
	background: url("block1-comments.png");
    margin: auto;
	max-width:540px;
    display: flex;
    justify-content: space-between;
    font-family:serif;
    padding:30px;
    border-radius: 5px;   

}
.block1-comments p {
	color: black;
	font-size: 18px;	
}

.block1-comments a {
	color: black;
	font-size: 18px;
}

.block2 {
	width: 300px;
	background: url("block2.png");
	border-radius: 5px;
	
}
.block2-info {
	background: url("block2-info.png") ;
	width: 330px;
	line-height: 38px;
	margin: 20px 0;
}
.block2-info p {
	color: white;
	margin-left: 30px;
	font-size: 17px;
	font-family: serif;
}


.block2-text p {
	color: #e1c9c4 ;
	font-size: 15px;
	padding:20px;
	line-height: 1.6;
	text-align:justify;
}

.block2-links ul {
	margin-left: 30px;
	list-style: none;
}

.block2-links ul li {
	line-height: 30px;
	width: 220px;
	border-bottom: 1px solid black;
}

.block2-links ul li a {
	text-decoration: none;
	color: white;
	font-size: 13px;
}

.block3-image {
	height: 280px;
	background: url("block3-image.png");
}

.block3 {
	max-width: 1020px;
	margin: auto;
	display: flex;
	justify-content: space-around;
}


.block3-text {
	margin: 30px;
	background: #592b21;
	padding: 20px;
	border-radius: 10px;
	border: 3px solid #50241a;
}

.block3-text h1 {
	color: white;
	font-family: serif;
	font-size:15px;
}

.block3-text p {
	color: #e1c9c4;
	font-family:sans-serif;
	margin-top: 20px;
	line-height: 2;

}

footer {
	height: 150px;
	background: url('footer.png');
	text-align: center;
	border:1px solid;
}

 footer p,
 footer a {
	margin-top:60px;
 	color: #e1c9c4;
 }
```

<h2>Вывод</h2>
Я зябора
