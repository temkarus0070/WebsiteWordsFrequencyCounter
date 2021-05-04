# TestTask
Для своей работы приложение требует ввода адреса вебстраницы, вторым необязательным аргументом является путь, куда будет сохранена веб-страница. По умолчанию это корень приложения и имя файла page.html
Проект можно открыть в IntelliJ IDEA и сделать запуск оттуда.
Также приложение можно запускать из консоли, и передать аргументы при вызове программы, все соглашения об аргументах приложения остаются нетронутыми.

Приложение написано с использованием функционала JDK 11.

Инструкция для запуска из консоли в windows, в других ОС суть такая же, но могут отличаться команды :

cd "[путь к корню приложения]\out\production\testTask"             (Теперь это текущая директория, включая директорию для файлов создаваемых приложением - log, page.html)
java Program      						(Запуск приложения без аргументов)

Если есть желание передать аргументы сразу, делаем это вот так
java Program "https://www.reddit.com/" "mypage.html"   (Запуск приложения с двумя аргументами) 
java Program "https://www.reddit.com/"   (Запуск приложения с одним,обязательным аргументом) 


Если при запросе ввода  ввести пустые строки в качестве адреса html страницы и пути к файлу, запустится тестовый метод и покажет работу приложения на некоторых веб-страницах.
В корне приложения находится log файл, в него будут записаны ошибки, возникающие во время работы приложения например ошибка при подключении к веб-ресурсу, ошибки файловой системы и т.д. 
