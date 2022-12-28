# Инструкция по работе с GIT

### Устновка GIT и VSCode
* [Установка Git для Windows, MAC, Linux](https://git-scm.com/downloads).
* [Установка VSCode для Windows, MAC, Linux](https://code.visualstudio.com/Download).

*При первом использовании Git необходимо представиться.*
*Для этого нужно ввести в терминале 2 команды:*<br/><span style='color:#4682B4'>**git config --global user.name «Ваше имя английскими буквами»**<br/>**config --global user.email ваша почта@example.com**</span>

# Основные команды GIT

* <span style='color:#4682B4'>git init</span> — инициализация локального репозитория
* <span style='color:#4682B4'>git status</span> — получить информацию от git о его текущем состоянии
* <span style='color:#4682B4'>git add</span> — добавить файл или файлы к следующему коммиту
* <span style='color:#4682B4'>git commit -m 'message'</span> — создание коммита
* <span style='color:#4682B4'>git log</span> — вывод на экран истории всех коммитов с их хеш-кодами
* <span style='color:#4682B4'>git checkout</span> — переход от одного коммита к другому
* <span style='color:#4682B4'>git checkout master</span> — вернуться к актуальному состоянию и продолжить работу
* <span style='color:#4682B4'>git diff</span> — увидеть разницу между текущим файлом и закоммиченным файлом

# Синтаксис язка Markdown

[Справочник по Markdown от Microsoft](https://docs.microsoft.com/ru-ru/contribute/markdown-reference)

![photo](photo.png)

# Ветки

* Для создания ветки, введите — <span style='color:#4682B4'>git</span> branch <span style='color:#4682B4'><branch_name></span> 
* Для уделания ветки, введите — <span style='color:#4682B4'>git</span> branch -d <span style='color:#4682B4'><branch_name></span> 
* Чтобы переключиться на нужную ветку, введите — <span style='color:#4682B4'>git</span> checkout <span style='color:#4682B4'><branch_name></span>
* Чтобы слить две ветки, введите — <span style='color:#4682B4'>git</span> merge <span style='color:#4682B4'><branch_name></span>

# Конфликты
* Если есть изменения в обеих ветках, жди беды, а может и не жди
# Возникновение конфликтов
* Конфликты это грустно, они могут возникать при слиянии
* А сейчас мы сделаем сам конфликт

## Как сделать pull reqest.

* Делаем fork (ответвление) репозитория
* Делаем git clone своей версии репозитория
* Создаем новую ветку и в нее вносим свои изменения
* Делаем commit
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request

