# Низкоуровневая работа с веб
# Цель работы
Освоить основные навыки обращения c Web из программы на Python, средства парсинга веб-страниц, соответствующие библиотеки.
# Дополнительные задания
+ При ответе вашего сервера посылайте некоторые основные заголовки:
+ + Date
+ + Content-type
+ + Server
+ + Content-length
+ + Connection: close.

![screenshot](web_screen/1.png)

Создайте файл настроек вашего веб-сервера, в котором можно задать прослушиваемый порт, рабочую директорию, максимальный объем запроса в байтах. Можете добавить собственные настройки по желанию. Файл настроек в формате JSON

![screenshot](web_screen/2.png)

![screenshot](web_screen/3.png)

Если файл не найден, сервер передает в сокет специальный код ошибки - 404.

![screenshot](web_screen/4.png)

Ошибка 404 так как такого файла нет 6. Сервер должен работать в многопоточном режиме.

![screenshot](web_screen/5.png)

Сервер должен вести логи в следующем формате: Дата запроса. IP-адрес клиента, имя запрошенного файла, код ошибки. В файле log.txt в корне сервера

![screenshot](web_screen/7.png)

Добавьте возможность запрашивать только определенные типы файлов (.html, .css, .js и так далее). При запросе неразрешенного типа, верните ошибку 403.

![screenshot](web_screen/8.png)


Реализуйте поддержку бинарных типов данных, в частночти, картинок.

![screenshot](web_screen/6.png)
![screenshot](web_screen/10.png)
