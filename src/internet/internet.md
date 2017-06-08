#Как устроен интернет?
- IP - Internet Protocol (ранее IP4, IPv6 - новые).
- Имя - домен, хостинг - сервер.

##Сайт:
- Находится на сервере
- Браузер понимает благодаря DNS (48 hrs) (ввод site.ru => браузер => DNS => IP)
- Доставка? служба - TCP/IP, посылка - http-пакеты (состоят из заголовков и тела - html-код)
- Как браузер читает? Детали - html, css, img. Инструкция - спецификация html/css
- Много http-запросов? Для http/1.1 критично, последовательно! Для http/2.0 не критично, параллельно!

##Человекопонятный процесс:
- Человек - сайт
- Дом - сервер
- Адрес - IP
- Номер квартиры - port программы (по умолчанию http :80, https :443)
- Комната - virtual host
- Имя - name.ru

##DNS
- медленная
- большая
- must be надежной (принцип простой, сложная реализация, закрытый доступ - только у регистратора по паспортным данным)
- получаем домен - ждем до 48 часов для распределения по системе DNS