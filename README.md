# html_specialist<br>
#Валидатор - контроль по коду хтмл по стандарту<br>
https://validator.w3.org/<br>
https://jigsaw.w3.org/css-validator/#validate_by_input
#Канал препода<br>
https://www.youtube.com/c/htmllabru<br>

#справочники по хтмл<br>
https://html.spec.whatwg.org/multipage/<br>
https://developer.mozilla.org/ru/docs/Web/HTML<br>
<br>
test<br>
https://forms.gle/x6bJggTi3WcaJ53c7

<br>
emmet:
heaer+section+nav+footer и система сразу напишет блоки
что бы сразу писать в несколько блоков ставим курсоры и нажимая таб доставляем курсоры <br>
#подгончик по большому выбору цветов с кодами для стайлов<br>
https://www.w3schools.com/Colors/colors_names.asp<br>
набор фоток
https://unsplash.com/s/photos/star



CSS<br>
Пишем только в head (правило хорошего тона)<br>
Примеры<br>
<code>
    <style>
        h1 {
            color: brown;
        }
        h3 {
            color: aqua;
        }
        
        
        div p {}

Найти все параграфы внутри див

<div>
	<section>
		<p>

=======================

div > p {}

найти параграфы в первой вложенности
и все это для ксс

============
псевдоклассы 
например
a:link
a:visited
a:active
a:hover - при наведении

:first-child
первые в структуре
допустим
h1:first-child
        p {
            font-family:Gill Sans;
        }
        #courses {
            background: lightgreen;
        }
        .dark {
            background-color: black;
            color: aliceblue;
        }
    </style>
</code>


Приоритеты селекторов:
<code>
!important
id
class
tag
*
</code>

Единицы измерения<br>

px - пиксель / 16 px размер текста по умолчанию<br>
html 16 px<br>
body 16 px<br>
em - относительная длина / 1em 16 px - это 1 размер родительского элемента (дефолт 16пх) Если вдруг body 2 em (32px) а p 2 em, то р уже 64 пх.<br>
1 rem == размеру текста по умолчанию - 16 px<br>

Цвета
в РГБ
RGB
red,orange,black
в 16 ричной системе
#000000 - черный
#ffffff - белый
#ff0000 - красный
в 10 тичной сисеме
#255,0,0
