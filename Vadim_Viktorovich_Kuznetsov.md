# Что такое Git?

![Git](Git_image.png)

* Git — совершенно абсолютный лидер по популярности среди современных систем управления версиями. Это развитый проект с активной поддержкой и открытым исходным кодом. Система Git была изначально разработана в 2005 году Линусом Торвальдсом — создателем ядра операционной системы Linux. Git применяется для управления версиями в рамках колоссального количества проектов по разработке ПО, как коммерческих, так и с открытым исходным кодом. Система используется множеством профессиональных разработчиков программного обеспечения. Она превосходно работает под управлением различных операционных систем и может применяться со множеством интегрированных сред разработки (IDE).

* Git — система управления версиями с распределенной архитектурой. В отличие от некогда популярных систем вроде CVS и Subversion (SVN), где полная история версий проекта доступна лишь в одном месте, в Git каждая рабочая копия кода сама по себе является репозиторием. Это позволяет всем разработчикам хранить историю изменений в полном объеме.

* Разработка в Git ориентирована на обеспечение высокой производительности, безопасности и гибкости распределенной системы.

# Основные команды Git

* git init - инициализация локального репозитория;
* git status - получить информацию от git о его текущем состоянии;
* git add - добавить файл или файлы к следующему коммиту;
* git commit -m "message" – создание коммита;
* git log – вывод на экран истории всех коммитов с их хеш-кодами;
* git checkout – переход от одного коммита к другому;
* git checkout master – вернуться к актуальному состоянию и продолжить работу;
* git diff – увидеть разницу между текущим файлом и закоммиченным файлом.

## Использование веток

* git branch <branch name> - создает новую ветку;
* git branch -  отображает список веток в репозитории;
* git branch -d <branch name> -удаление ветки;
* git branch -m <branch name> - изменение имени текущей ветки на <branch name>;
* git branch -a - вывод списка всех удаленных веток;
* git checkout <branch name> - переход на ветку <branch name>.

# Синтаксис языка Markdown
## Выделение текста. Списки.
* #Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка (поддерживается 6 уровней).
* = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки
первого (“=”) и второго (“-”) уровней.
* ** **Полужирное начертание** ** или __ __Полужирное начертание__ __.
*  **Курсивное начертание* * или _ _Курсивное начертание_ _.
* *** ***Полужирное курсивное начертание*** ***
* ~~ ~~Зачёркнутый текст~~ ~~.
*   Строка – ненумерованные списки, символ  “*” в начале строки.
* 1, 2, 3 … – нумерованные списки.
* Для того чтобы создать горизонтальную линию с использованием синтаксиса языка Markdown, необходимо поместить три (или более)дефиса или звездочки на отдельной строке текста.
******
Между ними возможно располагать пробелы.
## Ссылки.
* Чтобы поставить гиперссылку без анкора, нужно взять URL в угловые скобки <https://learn.microsoft.com/ru-ru/contribute/how-to-write-links>. С e-mail – аналогично: <v.v.kuznetsov@list.ru>.
Если вставлять с анкором, то тогда текст ссылки заключается в квадратные скобки, а адрес страницы – в круглые: [Использование ссылок в документации](https://learn.microsoft.com/ru-ru/contribute/how-to-write-links). Рядом с URL можно прописать тайтл, его объявляют в кавычках (он тоже остается внутри круглых скобок).
* Синтаксис Markdown для работы с картинками очень похожий. Разница в восклицательном знаке перед первыми квадратными скобками. ![logo Microsoft](https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE1Mu3b?ver=5c31) 

Ссылке на картинку тоже можно присвоить определенный ID.
***
## Цитаты и вставка кода.
* Если ссылки оформляются двумя угловыми скобками, то для цитаты нужна только одна такая скобка ">". 

> Добро пожаловать в Руководство по стилю письма Microsoft, ваше руководство по стилю письма и терминологии для любого общения — будь то приложение, веб-сайт или технический документ. Если вы пишете о компьютерных технологиях, это руководство для вас.

* Код можно вставлять как внутрь строк, так и отдельными блоками. Для соответствующей разметки используют грависы или обратные тики. Инлайн-код выделяют одиночными символами, а блоки – тройными. При оформлении целого блока можно указать язык программирования, чтобы подсветить соответствующий синтаксис. Примеры:

Код на Python:

```python

x = int(input())

if x > 0:

    print(x)

else:

    print(-x)

```
****
Код на JavaScript:

```javascript

let greeting1 = 'Father!';

console.log(greeting1);

let greeting2 = 'Mother!';

console.log(greeting2);

```
****
`x = int(input())`

`if x > 0:`

    `print(-x)`

`else:`

    `print(-x)`

