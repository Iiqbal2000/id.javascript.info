# Кнопка вверх-вниз

[importance 3]

Создайте кнопку навигации, которая помогает при прокрутке страницы.

Работать должна следующим образом:
<ul>
<li>Пока страница промотана меньше чем на высоту экрана вниз -- кнопка не видна.</li>
<li>При промотке страницы вниз больше, чем на высоту экрана, появляется кнопка "стрелка вверх". При нажатии на нее страница запоминает текущую прокрутку и прыгает вверх, а кнопка меняется на "стрелка вниз" и остается такой, пока посетитель не прокрутит вниз больше, чем один экран, после чего вновь изменится на "стрелка вверх".</li>
<li>Нажатие на "стрелка вниз" отправляет обратно на запомненную позицию.</li>
</ul>
Должен получиться удобный навигационный помощник.

Посмотрите, как оно должно работать, в ифрейме ниже. Прокрутите ифрейм, навигационная стрелка появится слева. 

[iframe border="1" height="200" link src="solution"]

В исходный документ включена кнопка.

