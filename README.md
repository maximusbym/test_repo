# Lesson 6

## Homework
1. Взять за основу домашку с Lesson 5.
2. Настроить RewriteRule в .htaccess, что бы все запросы переводились на index.php
3. В index.php делать проверку на полученные параметры и если мы получили, например, "localhost.com/form2/", то по "form2" определять, что нужно показать другую форму. 
3.1. А та, что на index.php показывалась, пусть так и показываеться при откритии корня сайта "localhost.com/"
4. На "localhost.com/form2/" показывать форму с текст. инпутом "имя" и инпут типа файл (форму для отправки файлов нужно POST и с атрибутом enctype="multipart/form-data").
5. Форма также должна записываться в текстовый файлик, но уже другой (НЕ /database/database.txt).
6. Файлы сохранять в папку /files.
7. Над формой показывать отправленные сообщения в формате:
<ИМЯ>
<ССЫЛКА НА ФАЙЛ>
...
