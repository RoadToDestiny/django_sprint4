Если сайт работает некорректно или вообще с ошибкой, то примените миграции и загрузите фикстуры.
python blogicum/manage.py migrate
python blogicum/manage.py loaddata db.json