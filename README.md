# DLE Charset Converter

Скрипт для конвертации базы данных + детальная инструкция по переводу сайта, работающего на CMS DataLife Engine, из windows-1251 в utf-8

# Инструкция по установке
- **Сделать полную копию сайта и БД** и залить всё локалку. В качестве локального сервера рекомендую использовать OpenServer. Если на сайте много картинок - можно не делать копию папки uploads.
- Залить содержимое папки upload в корень сайта (на локалке).
- Запустить скрипт по адресу **ваш_сайт/convert.php** и следовать инструкциям.
- После завершения всех работ выгрузить сайт на хостинг и настроить конфигуацию хостинга для работы в UTF-8. 
