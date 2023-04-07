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
			<p>СахГУ</p>
		</div>
			
		<div class="navigation">
			<li><a href="#" style="background: #a2231d;border-radius: 5px;padding:10px">Главная</a></li>
			<li><a href="#">Архив</a></li>
			<li><a href="#">Галерея</a></li>
			<li><a href="#">Об учреждение</a></li>
			<li><a href="#">Контакты</a></li>
		</div>
		
	</div>	

	<div class="banner">	
		<div class="banner-image">
			<img src="banner-image.jpg" alt="">
		</div>
			
		<div class="banner-text">
			<p>Дом в лесу с панорамными окнами</p>
		</div>	
	</div>
	
	<div class="main-image">
		<div class="main-block">

			<div class="block1">
			
				<div class="block1-info">
					<p>Опубликовано <a href="">мной</a> 07 апреля 2023г</p>
				</div>
				
				<h1>Сахалинский государственный университет</h1>

				<div class="block1-image">
					<img src="block1-image.jpg" alt="">
				</div>
				
				<div class="block1-text">
					<p>
						Основан в 1949 году (на основании распоряжения Совета министров РСФСР от 17 декабря 1948 года) как Южно-Сахалинский учительский институт, преобразованный в 1954 году в Южно-Сахалинский государственный педагогический институт. Изначально располагался в деревянном японском здании. 13 октября 1961 года в новом четырёхэтажном здании по ул. Ленина, 290 был торжественно открыт главный учебный корпус. В 1998 году преобразован в Сахалинский государственный университет, к которому было присоединено три колледжа, расположенных на территории Сахалинской области: Южно-Сахалинский педагогический, Александровск-Сахалинский и Сахалинский театральный. В 1999 году в состав университета вошел юридический факультет (филиал) ДВГУ, ныне Юридический институт СахГУ.
					</p>
				</div>
				
				<div class="block1-comments">
					<p>Опубликованые <a href="#"> Новости,<a href="#"><a href="#"> Дизайны,</a><a href="#"> Другое</a></p>
					<p><a href="#">7777 комментов</a></p>
				</div>
	
			</div>
			
			<div class="block2">
					
					<div class="block2-info">
						<p>О СахГУ</p>
					</div>

					<div class="block2-text">
						<p>
							Добро пожаловать на страницу Сахалинского государственного университета. Учеба, наука, внеучебная жизнь - все самое интересное из эпицентра событий. Без критиканства, но с долей иронии. :)
						</p>
					</div>

					<div class="block2-info"><p>Структура университета</p></div>

					<div class="block2-links">
						<ul>
							<li><a href="">ИФИиВ</a></li>
							<li><a href="">ИПиП</a></li>
							<li><a href="">ИЕНиТБ</a></li>
							<li><a href="">ТНИ</a></li>
							<li><a href="">ИПЭиУ</a></li>
						</ul>
					</div>

					<div class="block2-info"><p>Что-то ещё</p></div>

					<div class="block2-text">
						<p>В 1989 году между Хоккайдским университетом и Южно-Сахалинским педагогическим институтом был заключен первый международный договор о сотрудничестве. С этого момента началась международная деятельность будущего СахГУ.</p>
					</div>
			</div>
			
		</div>
	</div>
	
	<div class="block3-image">
	
		<div class="block3">
			
			<div class="block3-text">
				<h1>Виджеты</h1>
				<p>С помощью этого виджета можно отобразить заметный блок с текстовой информацией. Можно поменять заголовок, указать основной и дополнительный тексты и добавить внизу ссылку.</p>
			</div>

			<div class="block3-text">
				<h1>Виджеты</h1>
				<p>С помощью этого виджета можно отобразить заметный блок с текстовой информацией. Можно поменять заголовок, указать основной и дополнительный тексты и добавить внизу ссылку.</p>
			</div>

			<div class="block3-text">
				<h1>Виджеты</h1>
				<p>С помощью этого виджета можно отобразить заметный блок с текстовой информацией. Можно поменять заголовок, указать основной и дополнительный тексты и добавить внизу ссылку.</p>
			</div>
			
		</div>
	</div>
	
	<footer>
		
		<div class="footer-info">
			<p>Мой WebSite о СахГу | SakhGU by <a href=""> Maksim </a>| Photos by <a href=""> direction</a></p>
		</div>
		
	</footer>
	
</body>
</html>
```

2)CSS

```html
body {
	font-family: CURSIVE;
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
	font-size: 50px;
	font-family: CURSIVE;	
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
}

.banner-text {
	background: url("banner-text.png")no-repeat center;
	margin-bottom:20px;
}

.banner-text p{
	padding:15px;
	text-align: center;
	color: white;
	font-size:30px;
	font-family:cursive;
}	


.main-image {
	background: url("main-image.png");

}
.main-block {
	max-width: 1000px;
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
	border-radius: 10px;
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
	padding: 30px;
	font-size: 30px;
	color: #a2231d;
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
	padding: 30px;
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
	font-size: 15px;	
}

.block1-comments a {
	color: black;
	font-size: 15px;
}

.block2 {
	width: 300px;
	background: url("block2.png");
	border-radius: 10px;
	
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
	font-size: 15px;
	font-family: serif;

}


.block2-text p {
	color: #ddadaf ;
	font-size: 15px;
	padding:20px;
	line-height: 1.6;
	font-weight: 100;
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
	font-size: 15px;
}

.block3-image {
	height: 280px;
	background: url("block3-image.png");
}

.block3 {
	max-width: 1000px;
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
	color: #ddadaf;
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
 	color: #d8b1bf;
 }
```

<h2>Вывод</h2>
Я зябора
