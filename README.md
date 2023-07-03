### Властивості шрифту

font-family: "Ім'я шрифту", "Ім'я шрифту", тип шрифту</br>
Встановлює сімейство шрифту</br>
Типи шрифту:</br>
serif - шрифти із зарубками (антиквенні), типу Times;</br>
sans-serif - рубані шрифти (шрифти без зарубок або гротески), типовий представник - Arial;</br>
cursive - курсивні шрифти;</br>
fantasy - декоративні шрифти;</br>
monospace - моноширинні шрифти, ширина кожного символу в такому сімействі однакова (шрифт Courier).</br>

font-size
Визначає розмір шрифту елемента.

font-style:
Визначає накреслення шрифту - звичайне, курсивне або похиле.
normal - Звичайне накреслення тексту.
italic - Курсивне накреслення. 
oblique - Похиле накреслення. Курсив і похилий шрифт за всієї їхньої схожості не одне й те саме. Курсив це спеціальний шрифт, що імітує рукописний, а похилий утворюється шляхом нахилу звичайних знаків вправо. 

font-weight:
Встановлює насиченість шрифту.
100 - thin
300 - lite
400 - normal
500 - medium
600 - semibold
700 - bold
900 - black

###Властивості тексту

color
Визначає колір тексту. Для завдання кольорів зазвичай використовуються числа в шістнадцятковому коді, 
або за допомогою RGB.

text-align
Визначає горизонтальне вирівнювання тексту в межах елемента. 
center - Вирівнювання тексту по центру.
justify - Вирівнювання по ширині, що означає одночасне вирівнювання по лівому і правому краю. Щоб виконати цю дію браузер у цьому випадку додає пробіли між словами.
left - Вирівнювання тексту по лівому краю. 
right - Вирівнювання тексту по правому краю.

text-decoration
Додає оформлення тексту у вигляді його підкреслення, перекреслення, лінії над текстом і миготіння. 
Одночасно можна застосувати більше одного стилю, перераховуючи значення через пробіл. Ця властивість успадковується і може приймати значення:
line-through - Створює перекреслений текст.
overline - Лінія проходить над текстом.
underline - Встановлює підкреслений текст. 
none - Скасовує всі ефекти, зокрема й підкреслення у посилань, яке задано за замовчуванням.

text-shadow: горизонтальне_зміщення вертикальне_зміщення розмір колір;
Додає тінь до тексту.
Прмер text-shadow: 1px 1px 1px #000;

text-transform
Керує перетворенням тексту на великі або прописні символи.
capitalize - Перший символ кожного слова в реченні буде заголовним. Решта символів свій вигляд не змінюють.
lowercase - Усі символи тексту стають малими (нижній регістр). 
uppercase - Усі символи тексту стають великими (верхній регістр).
none - Не змінює регістр символів.

text-indent
Встановлює величину відступу першого рядка блоку тексту. При змінюється, якщо нам потрібно створити щось типу червоного рядка.

letter-spacing
Визначає інтервал між символами (буквами). Використовується коли потрібно розрядити текст.

line-height
Встановлює міжрядковий інтервал тексту. Широко застосовується під час верстки тексту.

white-space
Керує властивостями пробілів між словами. Застосовується в основному зі значенням 
nowrap яке забороняє перенесення рядка. Таким чином весь текст відображається в один рядок і не ламається. Значення normal поверне все як було.

word-spacing
Встановлює інтервал між словами. 

###box-sizing
Застосовується для зміни алгоритму розрахунку ширини та висоти елемента. 
Властивість успадковується.
content-box - Ґрунтується на стандартах CSS, при цьому властивості width і height задають ширину і висоту контенту і не включають в себе значення відступів, полів і кордонів.
border-box - Властивості width і height містять значення полів і меж, але не відступів (margin). Ця модель використовується браузером Internet Exporer у режимі несумісності.
padding-box - Властивості width і height містять значення полів, але не відступів (margin) і меж (border).
(https://github.com/vlad13578/web/blob/main/img/git/QIP%20Shot%20-%20Screen%205556.png?raw=true) 
_________________________________________

padding
Внутрішній відступ елемента
У разі зазначення поля у відсотках, значення рахується від ширини батька елемента.
Властивість не успадковується.

padding: з_всіх_сторон;
padding: зверху праворуч знизу ліворуч;
padding: зверху_знизу справа_зліва;
padding: зверху справа_зліва знизу;
Відступ зверху і знизу не діє на рядкові теги

=========================================
margin
Зовнішній відступ елемента
При вказівці поля у відсотках, значення рахується від ширини батька елемента.
Властивість не успадковується.
Значення може бути як позитивним, так і негативним числом.

margin: з_всіх_сторон;
margin: зверху праворуч знизу ліворуч;
margin: зверху_знизу справа_зліва;
margin: зверху справа_зліва знизу;

Відступ зверху і знизу не діє на термінові теги

=========================================
width
Встановлює ширину блокових тегів і деяких рядкових (наприклад img)
Властивість не успадковується.
width:100px;
width:10%;

=========================================
max-width
Встановлює максимальну ширину блокових тегів і деяких рядкових (наприклад img)

=========================================
min-width
Встановлює мінімальну ширину блокових тегів і деяких рядкових (наприклад img)

=========================================
height:
Встановлює висоту блокових тегів і деяких рядкових (наприклад img)
Властивість не успадковується.
height:100px;
height:10%;

=========================================
min-height
Властивість не успадковується.

=========================================
max-height
Властивість не успадковується.

=========================================
overflow 
Керує відображенням вмісту блочного елемента
visible - Відображається весь вміст елемента, навіть за межами встановленої висоти та ширини. 
hidden - Відображається тільки область усередині елемента, решта буде прихована.
scroll - Завжди додаються смуги прокручування.
auto - Смуги прокручування додаються лише за необхідності.

=========================================
display:
Багатоцільова властивість, яка визначає, як елемент повинен бути показаний у документі.
Властивість не успадковується.

block – елемент показується як блоковий. Застосування цього значення для вбудованих елементів, наприклад тега <span>, змушує його вести подібно до блоків - відбувається перенесення рядків на початку і в кінці вмісту.
inline - Елемент відображається як інтегрований. Використання блокових тегів, таких як <div> та <p>, автоматично створює перенос і показує вміст цих тегів з нового рядка. Значення inline скасовує цю особливість, тому вміст блокових елементів починається з місця, де закінчився попередній елемент.
inline - block - Це значення генерує блоковий елемент, який обтікається іншими елементами веб-сторінки подібно до вбудованого елемента. Фактично такий елемент за своєю дією схожий на елементи, що вбудовуються (на зразок тега <img>). При цьому його внутрішня частина форматується як блоковий елемент, а сам елемент як вбудований.
none - тимчасово видаляє елемент із документа. Займане ним місце не резервується і веб-сторінка формується так, як елемента і не було.

=========================================
border
Універсальна властивість border дає змогу одночасно встановити товщину, 
стиль і колір кордону навколо елемента.
border: 1px solid #000; (розмір стиль колір)
Основні стилі -solid dotted dashed

=========================================
border-radius
Встановлює радіус заокруглення куточків блоку.
border-radius:50%; - кргуг
Можна використовувати разом з overflow: hidden;

=========================================
outline
Універсальна властивість, що одночасно встановлює колір, 
стиль і товщину зовнішньої межі на всіх чотирьох сторонах елемента. 
На відміну від лінії, що задається через border, властивість outline 
не впливає на положення блоку та його ширину. 
Також не можна задати параметри лінії на окремих сторонах елемента, 
outline застосовується відразу до всіх чотирьох сторін. 

=========================================
https://getcssscan.com/css-box-shadow-examples
box-shadow
Додає тінь до елемента.
box-shadow: зсув_по_гориз зсув_по_верт радіус відстань
Можна додати багато тіней. На тінь впливає властивість border-radius.

=========================================
opacity
Визначає рівень прозорості елемента.
Відмінність opacity:0; від display:none; в тому, що блок не забирається з верстки, а тільки стає прозорим, тобто місце, яке він займає, залишається. Так само, з прозорими елементами все ще можна взаємодіяти, наприклад, клікати за посиланнями.

=========================================
visibility
Призначений для відображення або приховування елемента.
Відмінність visibility: hidden; від display:none; в тому, що блок не забирається з верстки, а тільки ховається, тобто займане ним місце залишається.
Відмінність visibility: hidden; від opacity:0; у тому що блок приховується і взаємодіяти з ним не можна.

=========================================
https://www.colorzilla.com/gradient-editor/
https://fls.guru/cssbackground.html

background:
Універсальна властивість background дає змогу встановити одночасно кілька характеристик фону, а саме:

=======================================================
background-color - Визначає колір фону елемента.

=======================================================
background-image - Встановлює фонове зображення для елемента.

Так само значенням властивості можна вказати градієнт:
лінійний:
background:linear-gradient(to top, #fefcea, #f1da36); 
радіальний:
background:radial-gradient(ellipse at center, rgba(30,87,153,1) 0%,rgba(41,137,216,1) 50%,rgba(32,124,202,1) 51%,rgba(125,185,232,1) 100%);

Детальніше про градієнти:
http://htmlbook.ru/css3-na-primerakh/lineinyi-gradient

Інструмент створення готового коду:
https://www.colorzilla.com/gradient-editor/

=======================================================
background-position - Задає початкове положення фонового зображення, встановленого за допомогою властивості background-image.

=======================================================
background-repeat - Визначає, як буде повторюватися фонове зображення, встановлене за допомогою властивості background-image.
no-repeat - Встановлює одне фонове зображення в елементі без його повторень, положення якого визначається властивістю background-position (за замовчуванням у лівому верхньому кутку). Аналогічно no-repeat no-repeat.
repeat - Фонове зображення повторюється по горизонталі та вертикалі. Аналогічно repeat repeat.
repeat-x - Фоновий малюнок повторюється тільки по горизонталі. Аналогічно repeat no-repeat.
repeat-y - Фоновий малюнок повторюється тільки по вертикалі. Аналогічно no-repeat repeat.
inherit - Успадковує значення батька.
space - Зображення повторюється стільки разів, щоб повністю заповнити область; якщо це не вдається, між картинками додається порожній простір.
round - Зображення повторюється так, щоб в області помістилося ціле число малюнків; якщо це не вдається зробити, то фонові малюнки масштабуються.

=======================================================
background-attachment - Встановлює, чи буде прокручуватися фонове зображення разом із вмістом елемента.
fixed - Робить фонове зображення елемента нерухомим. 
scroll - Дозволяє переміщатися фону разом із вмістом.
inherit - Успадковує значення батька.
local - Фон фіксується з урахуванням поведінки елемента. Якщо елемент має прокрутку, то фон буде прокручуватися разом із вмістом, але фон, що виходить за рамки елемента, залишається на місці.

=======================================================
background-size - Масштабує фонове зображення відповідно до заданих розмірів.
<значення> - Задає розмір у будь-яких доступних для CSS одиницях. 
<відсотки> - Задає розмір фонової картинки у відсотках від ширини або висоти елемента. 
auto - Якщо задано одночасно для ширини і висоти (auto auto), розміри фону залишаються початковими; якщо тільки для одного боку картинки (100px auto), то розмір обчислюється автоматично виходячи з пропорцій картинки.
cover - Масштабує зображення зі збереженням пропорцій так, щоб його ширина або висота дорівнювала ширині або висоті блоку.
contain - Масштабує зображення зі збереженням пропорцій таким чином, щоб картинка цілком помістилася всередину блоку. 
Якщо встановлено одне значення, воно задає ширину фону, друге значення приймається за auto. Пропорції картинки при цьому зберігаються. Використання двох значень через пробіл задає ширину і висоту фонової картинки.

=======================================================
Властивість background дає змогу задати кілька зображень через кому, 
причому зі своїми налаштуваннями позиціонування, маштабування і прокрутки
======================================================= */

Синтаксис, тобто правило запису псевдокласів простий, ми пишемо селектор класу або селектор типу 
ставимо двокрапку, пишемо той чи інший псевдослас і вже після цього відкриваємо фігурні 
дужки і пишемо потрібні CSS параметри:
Селектор:Псевдоклас { параметри стилю }

================================================================================================================
 Псевдокласи стану.

:hover
Спрацьовує при наведенні на елемент, часто застосовується застосовується як для посилань так і для будь-якого іншого елемента.

:active
Спрацьовує при натисканні на елемент. В основному застосовується до посилань і кнопок.

:visited
Спрацьовує для відвіданих посилань

:focus
Спрацьовує при отриманні елементом фокусу. Часто застосовується до елементів форм. Наприклад інпутів.

================================================================================================================
### Псевдокласи положення в коді.

:first-child
Звернення до першого елемента в блоці

:last-child
Звернення до останнього елемента в блоці

:nth-child(порядковий номер елемента)
Звернення до конкретних елементів у блоці

odd - Звертається до елементів із непарними номерами
even - Звертається до елементів із парними номерами

================================================================================================================

### Псевдоелементи 
- це селектори, які визначають область елементів, яка від початку 
відсутня в дереві документа. Ця область створюється штучно за допомогою CSS.

Псевдоелемент :first-line задає стиль першого рядка форматованого тексту. 
Довжина цього рядка залежить від багатьох чинників, таких як використовуваний шрифт, 
розмір вікна браузера, ширина блоку, мови тощо. У правилах стилю допустимо 
використовувати тільки властивості, що стосуються шрифту, зміни кольору тексту і фону.

=================================================================================
Псевдоелемент :first-letter визначає стиль першого символу в тексті елемента, 
до якого додається. 
До цього псевдоелемента можуть застосовуватися тільки стильові властивості, 
пов'язані з властивостями шрифту, полями, відступами, межами, кольором і фоном.

=================================================================================
Псевдоелемент :before застосовується для відображення бажаного контенту до вмісту елемента, 
до якого він додається. Працює спільно з властивістю content. 

При додаванні :before до блочного елементу, значення властивості display може бути тільки: block, inline, none, list-item. 
Усі інші значення трактуватимуться як block.
У разі додавання :before до вбудованого елемента, display обмежений значеннями inline і none. 
Усі інші будуть сприйматися як inline.

=================================================================================
Псевдоелемент, який використовується для виведення бажаного тексту після вмісту елемента, 
до якого він додається. Псевдоелемент :after працює спільно з властивістю content. 

Під час додавання :after до блочного елемента, значення властивості display може бути тільки: 
block, inline, none, list-item. Усі інші значення трактуватимуться як block.
У разі додавання :after до вбудованого елемента, display обмежений значеннями inline і none. 
Усі інші будуть сприйматися як inline.

=================================================================================
::-ms-clear {}
Задає стиль кнопки для очищення текстового поля. Початково цю кнопку не видно, 
вона з'являється в правій частині поля тільки під час введення тексту.
Тільки IE

=================================================================================
::-moz-focus-inner{}
Задає стиль внутрішньої частини елемента
Тільки FireFox

=================================================================================

### Властивість position
https://fls.guru/cssposition.html
Встановлює спосіб позиціонування елемента відносно вікна браузера або інших об'єктів 
на веб-сторінці. Допоміжні властивості left, right, top і bottom керують положенням елемента, 
а z-index керує накладанням один на одного по осі Z.

Значення:
static - елемент позиціонується відносно батька і сусідніх елементів
relative - елемент позиціонується як static, але можна рухати його щодо свого положення
absolute - елемент позиціонується відносно найближчого батька з relative, absolute, fixed і sticky
fixed - елемент позиціонується відносно вікна браузера
sticky - елемент позиціонується як static але коли верхня межа елемента буде 
перебуватиме на відстані, зазначеній у параметрі top, від верхньої межі вікна браузера (або зазначеній у параметрі bottom від нижньої), 
він залишиться в цьому положенні щодо вікна доти, доки його нижня межа 
не упреться в інший sticky елемент або кінець батьківського елемента
inherit - бере значення від батька

==========================================================
Властивості:
top, bottom, left і right - керують положенням елемента зверху знизу зліва і справа.
Значення можуть вказуються в тому числі у відсотках і можуть мати негативні значення.
Працюють з елементами, до яких застосовано один із параметрів 
position:relative,position:absolute,position:fixed і position:sticky (тільки top або bottom)

==========================================================
Властивість: z-index
Керує накладанням один на одного елементів із
параметрами position:relative,position:absolute,position:fixed по осі Z */

========================================================================
https://nomail.com.ua/
Google Fonts:
https://fonts.google.com/
Конвертер шрифтів:
http://www.font2web.com/

========================================================================
@font-face {
	font-family: 'Ім'я шрифту';
	font-display: swap;
	src: url("../fonts/файл шрифту.eot");
	src: local("O"), url("../fonts/файл шрифту.woff") format("woff"), 
			url("../fonts/файл шрифту.ttf") format("truetype"), 
			url("../fonts/файл шрифту.svg") format("svg");
	font-weight: normal;
	font-style: normal;
}

========================================================================
font-family: "Ім'я шрифту", "Ім'я шрифту", тип шрифту
Встановлює сімейство шрифту
Типи шрифту:
serif - шрифти із зарубками (антиквенні), типу Times;
sans-serif - рубані шрифти (шрифти без зарубок або гротески), типовий представник - Arial;
cursive - курсивні шрифти;
fantasy - декоративні шрифти;
monospace - моноширинні шрифти, ширина кожного символу в такому сімействі однакова (шрифт Courier).

========================================================================
font-weight:
Встановлює насиченість шрифту.
100 - thin
200 - UltraLite
300 - lite
400 - normal
500 - medium
600 - semibold
700 - bold
800 - Heavy
900 - black

========================================================================
