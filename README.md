<!DOCTYPE html>
<html>
<head>
  <title> Марченко Степан </title>
</head>
<body>
<h1>Сайт</h1>
<ol>
<li> <a href="example.com">Абсолютная гиперссылка</a> </li>
<li><a href="https://example.com">Абсолютная гиперссылка с https</a></li>
<li>
	<a href="ftp://example.com/file.zip"> Cсылкa на файл на сервере FTP без авторизации </a>
</li>
<li>
	<a href="ftp://user:password@example.com/file.zip">Cсылкa на файл на сервере FTP с авторизацией </a>
</li>

<li>
	<a href="http://exemple.com/about"> Гиперссылка на фрагмент страницы некоторого сайта </a>
</li>

<li>
	<a href="#frag"> Ссылка на фрагмент текущей страницы </a>
</li>
<li>
	<a href="http://carshop.ru/car/reno?page">Сылка с двумя параметрами URL</a></li>
<li>
	Список ссылок основной навигации сайта с подписями title
</li>
<ul>
<li><a href="index.html" title="Главная страница" target="_blank"> Главная страница </a></li>
<li><a href=" " title="Обновить" target="_blank">Обновить</a></li>
<li><a href="../index.html"
title="Относительная ссылка на страницу уровнем выше" target="_blank"> Относительная ссылка на страницу уровнем выше</a></li>
</ul>
<li><a>ссылка без href</a></li>
<li><a href="">Ссылка с пустым href</a></li>
<li><a href="http://example.ru" rel="nofollow">Ссылка по которой запрещен переход поисковикам</a></li>
<li>
	<noindex>
		<a href="http://example.ru" rel="nofollow" target="_blank"> Ссылка, запрещенная для индексации поисковиками </a>   
	 </noindex>
	</li>
<li>
	<p>Контекстная ссылка в тексте 
		<a href="http://example.ru" target="_blank">абзаца</a></p></li>
		<li>
			<a href="http://example.com/" target="_blank"><img src="jojo.jpg" width="120" height="100"></a></li>
			<li>
				<li>
					<img src="jojo.jpg" usemap="jojo.jpg" width="500" height="400">
					<map name="jojo">
						<area title="asd" alt="rect" coords="0,0,300,200" shape="rect" href="http://example.com">
						<area title="asd1" alt="cricle" coords="250,300,75" shape="cricle">
					</map>
<li>
	<a href="/index.html">
	Относительная ссылка на страницу в текущем каталоге</a></li>
	<li>
		<a href="about/about.html">Относительная ссылка на страницу в каталоге about</a></li>
		<li>
			<a href="../">Относительная ссылка в текущем каталоге уровнем выше текущегo</a></li>
		<li>
			<a href="../../">Относительная ссылка в текущем каталоге двумя уровнями выше текущегo</a></li>
			<li>
			<a href="/">Сокращенная ссылка на главную</a></li>
			<li>
			<a href="demo.html">Cсылка на внутреннюю страницу</a></li>









</ol>

<form action="/" method="POST">
	<h1 align="center">Информация о себе</h1>
	<h1>
	<label>
	Имя: 
	<input type="text">
	</label>
	</h1> 
	<h1>
		<label>
			E-mail:
			<input type="text">
		</label>
	</h1>
	<p>
		<label>
			Дата рождения
			<input type="date">
		</label>
	</p>
<p> Пол:
	<br>
	<lable>
	<input name="radio1" type="radio" value="1">Мужской
</lable>
<label>
	<input name="radio2" type="radio" value="2">Женский
</label>
</p>
<p>
	Кол-во конечностей:
	<br>
	
		<input name="1" type="radio" value="1">1
	
	
		<input name="2" type="radio" value="2">2
	
	<br>
	
		<input name="3" type="radio" value="3">3
	
	
		<input name="4" type="radio" value="4">4

	
</p>
<h4> 
<lable for> Способность: </lable></h4>
<select name="Способность:">
	<option value="Бессмертие">Бессмертие</option>
	<option value="Невидимость">Невидимость</option>
	<option value="Чтение мыслей">Чтение мыслей</option>
</select>
<h4>
	<lable>
		Биография:
		<textarea style="margin: 1px;"> </textarea>
</lable>
</h4>
<p>
	<lable>
		С контрактом ознакомлен.
		<br>
		<input type="radio">
	</lable>
</p>
<p>
	<input type="submit" value="Отправить">
</p>
</form>

</body>
</html>
