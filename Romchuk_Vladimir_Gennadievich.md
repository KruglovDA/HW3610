# **Инструкция по GIT**
1. **Что такое GIT?**  
Git — это набор консольных утилит, которые отслеживают и фиксируют изменения в файлах (чаще всего речь идет об исходном коде программ, но вы можете использовать его для любых файлов на ваш вкус). Изначально Git был создан Линусом Торвальдсом при разработке ядра Linux. Однако инструмент так понравился разработчикам, что в последствии, он получил широкое распространение и его стали использовать в других проектах. С его помощью вы можете сравнивать, анализировать, редактировать, сливать изменения и возвращаться назад к последнему сохранению. Этот процесс называется контролем версий.
2. **Настройка GIT**  
*Откройте терминал и запустите команды*:    
* git config --global user.name "My Name"
* git config --global user.email myEmail@example.com
3. **Создание репозитория**  
Чтобы создать новый репозиторий, нам нужно открыть терминал, зайти в папку нашего проекта и выполнить команду **git.init**. Это включит приложение в этой конкретной папке и создаст скрытую директорию .git, где будет храниться история репозитория и настройки.
4. **Комманды ГИТ** 
* **git init** - создание репозитория (папку которую будем отслеживать)
* **git add new file.txt** - добавляем отслеживаемый файл
* **git commit m "комментарий"** - сохраняем файл + комментарий 
* **git commit -a -m "комментарий"** - добваляем и сохраняем файл
* **git log** - открыть журнал изменений
* **git checkout** - откатить изменения. 
* **git status** -  статус файла
5. **Работа с ветками**  
* создание новой ветки : git branch "имя ветки"
* просмотр веток : git branch
* переключение веток : git checkout "имя ветки"
* слияние ветки : git merge 
* удаление ветки : git branch -d "имя ветки"
6. **Настройка .gitignore**  

В большинстве проектов есть файлы или целые директории, в которые мы не хотим (и, скорее всего, не захотим) коммитить. Мы можем удостовериться, что они случайно не попадут в git add -A при помощи файла .gitignore. 
* Создайте вручную файл под названием .gitignore и сохраните его в директорию проекта.  
* Внутри файла перечислите названия файлов/папок, которые нужно игнорировать, каждый с новой строки.  
* Файл .gitignore должен быть добавлен, закоммичен и отправлен на сервер, как любой другой файл в проекте.

**Вот и все! Наше руководство окончено.**  
! [картинка](image.jpg)