<!DOCTYPE html>
<html>

    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>НАЧАЛО РАБОТЫ С BRACKETS</title>
        <meta name="description" content="Интерактивное руководство по началу работы в Brackets.">
        <link rel="stylesheet" href="main.css">
    </head>
    <body>

		<h1>НАЧАЛО РАБОТЫ С BRACKETS</h1>
		<h2>Ваше личное руководство!</h2>
		
		<!--
			СДЕЛАНО С <3 И JAVASCRIPT
		-->
		
		
		<p>
			Добро пожаловать в раннюю версию Brackets, нового редактора с открытым исходным
			кодом для веба следующего поколения. Мы большие фанаты стандартов и хотим построить лучший
			инструмент для JavaScript, HTML и CSS и связанных с ними открытых веб-технологий. Это наше
			скромное начало.
		</p>
		
		<!--
			ЧТО ТАКОЕ BRACKETS?
		-->
		<p>
			<em>Во многих отношениях, Brackets необычный редактор.</em>
			Одна примечательная особенность в том, что этот редактор написан на JavaScript,
			HTML and CSS. Это означает, что большинство пользователей Brackets имеют навыки
			необходимые для доработки и расширения редактора. На самом деле, мы используем Brackets
			каждый день для того, чтобы улучшать Brackets. Он так же имеет несколько особенностей
			вроде Быстрого Редактирования, Интерактивного Просмотра и других, которые вы не сможете
			найти в других редакторах.
			Читайте далее для того чтобы узнать, как использовать эти особенности редактора.
		</p>
		
		
		<h2>Мы испытываем несколько новых штук</h2>
		
		<!--
			ОТНОШЕНИЯ МЕЖДУ HTML, CSS И JAVASCRIPT
		-->
		<h3>Быстрое редактирование CSS и JavaScript</h3>
		<p>
			Теперь никакого переключения между документами и потери контекста. Во время редактирования HTML
			используйте сочетание клавиш <kbd>Cmd/Ctrl + E</kbd> для открытия быстрого редактора, который показывает
			все связанное с этой строкой CSS. Сделайте изменение CSS-стилей, нажмите <kbd>ESC</kbd> и вернитесь обратно
			к редактированию HTML. Или просто оставьте блок с CSS-правилами открытым, и они станут частью вашего
			HTML-редактора. Если вы нажмете <kbd>ESC</kbd> вне быстрого редактора, все CSS-правила закроются.
		</p>
		
		<samp>
			Хотите увидеть это в действии? Поставьте курсор на теге <!-- <samp> --> выше и нажмите
			<kbd>Cmd/Ctrl + E</kbd>. Вы должны увидеть, как выше появится быстрый редактор CSS. Справа вы
			увидите список CSS-правил, которые относятся к этому тегу. Просто прокрутите правила вниз, используя
			<kbd>Alt + Up/Down</kbd>, чтобы найти то, которое вы хотите отредактировать.
		</samp>
		
		<a href="screenshots/quick-edit.png">
			<img alt="A screenshot showing CSS Quick Edit" src="screenshots/quick-edit.png" />
		</a>
		
		<p>
			Вы так же можете использовать эти горячие клавиши при работе с кодом JavaScript,
			для того, чтобы увидеть содержание функции, просто наведите курсор на её название.
			На данный момент внутри встроенного редактора нельзя открыть еще один, поэтому вы можете
			использовать только Быстрое Редактирование, когда курсор находится в "полноэкранном" редакторе.
		</p>
		
		<!--
			ИНТЕРАКТИВНЫЙ ПРОСМОТР
		-->
		<h3>Просматривайте изменения CSS вживую в браузере!</h3>
		<p>
			Вы знаете эти пляски с "сохранить/перезагрузить", которые мы делаем годами? Когда вы делаете
			изменения в вашем редакторе, нажимаете сохранить, переключаетесь в браузер и затем нажимаете
			перезагрузить, чтобы наконец увидеть результат? Вместе с Brackets этого больше не придется делать.
		</p>
		<p>
			Brackets откроет <em>прямое соединение</em> с вашим локальным браузером и направит ваши изменения CSS, как
			только вы их напечатаете! Вы, возможно, уже делали что-то подобное с инструментами, встроенными в браузер,
			но с Brackets больше нет нужды копировать и вставлять финальный CSS обратно в редактор.
			Ваш код запускается в браузере, но живет в вашем редакторе!
		</p>
		<h3>Подсвечивание HTML-элементов и CSS-правил в реальном времени</h3>
		<p>
		   С Brackets стало проще понять, как изменения в HTML и CSS отразятся на странице. Когда ваш курсор находится на
		   CSS-правиле, Brackets подсветит все затронутые элементы в браузере. То же самое и с редактированием HTML-файла,
		   Brackets будет подсвечивать соответсвующие HTML-элементы в браузере.
		</p>
		<samp>
			Если у вас есть установленный Google Chrome, вы можете попробовать это сами. Нажмите на иконку
			молнии в правом верхнем углу или нажмите <kbd>Cmd/Ctrl + Alt + P</kbd>. Когда Интерактивный Просмотр
			включен в HTML-документе, все подключенные CSS-документы могут редактироваться в реальном
			времени. Иконка изменится с серой на золотую, когда Brackets установит соединение с вашим браузером.
			
			Теперь, поставьте курсор на теге <!-- <img> --> выше и используйте <kbd>Cmd/Ctrl + E</kbd>, чтобы
			открыть записанные CSS-правила. Попробуйте изменить размер границы с 10 пикселя до 20 или изменить
			цвет фона с "transparent" на "hotpink". Если Brackets и ваш браузер работают вместе, вы увидите, как ваши
			изменения мгновенно отразятся в вашем браузере. Круто, правда?
		</samp>
				
		<p class="note">
			Сегодня, Brackets поддерживает Интерактивный Просмотр только для CSS. Сейчас мы работаем над поддержкой
			Интерактивного Просмотра для HTML и JavaScript. В текущей версии вы не увидите изменений в вашем HTML-
			или JavaScript-файле до тех пор, пока не сохраните документ. Интерактивный Просмотр работает только с
			Google Chrome. Но в будушем мы планируем добавить эту возможность для всех основных браузеров.
		</p>
		<h3>Быстрый просмотр</h3>
		<p>
			Для тех из нас, кто до сих пор не запомнил значения цветов для HEX или RGB, Brackets позволяет быстро и просто
			посмотреть напрямую, какой цвет используется. В любом CSS- или HTML-файле, просто наведите курсор на значение
			цвета или градиента и Brackets автоматически отобразит этот цвет/градиент. То же самое и с изображениями:
			просто наведите курсор на ссылку с изображением в редакторе и Brackets выведет миниатюру этого изображения.
		</p>
				
		<samp>
			  Попробуйте быстрый просмотр сами, поместите курсор на тэг <!-- <body> --> вверху этого документа и нажмите
			  <kbd>Cmd/Ctrl + E</kbd> для того, чтобы открыть быстрый редактор CSS. Сейчас просто наведите курсор на любое
			  значение цвета в CSS. Вы так же можете увидеть это в действии с градиентом, открыв быстрый редактор CSS на
			  тэге <!-- <html> --> и наведя курсор на любое значение фонового рисунка. Попробуйте быстрый просмотр изображений,
			  поместите ваш курсор на любой скриншот в этом документе.
		</samp>
		
		<!--
			РАССКАЖИТЕ, ЧТО ВЫ ДУМАЕТЕ
		-->
		<h2>Принимайте участие</h2>
		<p>
			Brackets &mdash; проект с открытым исходным кодом. Веб-разработчики со всех уголков мира способствуют
			созданию лучшего редактора кода. Многие разрабатывают дополнения, которые расширяют возможности
			Brackets. Расскажите нам, что вы думаете, поделитесь идеями или непосредственно поддержите проект.
		</p>
		<ul>
			<li><a href="http://brackets.io">Brackets.io</a></li>
			<li><a href="http://blog.brackets.io">Блог команды Brackets</a></li>
			<li><a href="http://github.com/adobe/brackets">Brackets на GitHub</a></li>
			<li><a href="http://github.com/adobe/brackets/wiki">Brackets Wiki</a></li>
			<li><a href="http://groups.google.com/group/brackets-dev">Почтовая рассылка разработчиков Brackets</a></li>
			<li><a href="https://twitter.com/#!/brackets">@Brackets в Twitter</a></li>
			<li>Общайтесь с разработчиками Brackets в IRC в #brackets на Freenode</li>
		</ul>

    </body>
</html>
<!--

    [[[[[[[[[[[[[[[      ]]]]]]]]]]]]]]]
    [::::::::::::::      ::::::::::::::]
    [::::::::::::::      ::::::::::::::]
    [::::::[[[[[[[:      :]]]]]]]::::::]
    [:::::[                      ]:::::]
    [:::::[                      ]:::::]
    [:::::[                      ]:::::]
    [:::::[                      ]:::::]
    [:::::[     CODE THE WEB     ]:::::]
    [:::::[  http://brackets.io  ]:::::]
    [:::::[                      ]:::::]
    [:::::[                      ]:::::]
    [:::::[                      ]:::::]
    [:::::[                      ]:::::]
    [::::::[[[[[[[:      :]]]]]]]::::::]
    [::::::::::::::      ::::::::::::::]
    [::::::::::::::      ::::::::::::::]
    [[[[[[[[[[[[[[[      ]]]]]]]]]]]]]]]

-->
