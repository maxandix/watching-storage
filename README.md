# Пульт охраны банка

Это внутренний репозиторий для для сотрудников банка "Сияние". 
Если вы попали в этот репозиторий случайно, то вы не сможете его запустить, 
т.к. у вас нет доступа к БД, но можете свободно использовать код вёрстки или посмотреть как реализованы запросы к БД.

Пульт охраны - это сайт, который можно подключить к удаленной базе данных
с визитами и карточками пропуска сотрудников нашего банка.

### Как установить:

- Скачайте код
- Запросите доступ к БД у менеджера вашего банка и затем установите значения переменных окружения:
  - `DB_HOST` - хост
  - `DB_PORT` - порт
  - `DB_NAME` - имя базы данных
  - `DB_USER` - имя пользователя
  - `DB_PASSWORD` - пароль пользователя

Для доступа к БД используется движок: `django.db.backends.postgresql_psycopg2`
- Установите значения переменных окружения `SECRET_KEY` и `DEBUG`
- Установите Python версии не ниже 3.5. 
- Затем используйте `pip` для установки зависимостей:
```
pip install -r requirements.txt
```

### Как запустить:
- Запустите сайт командой `python manage.py runserver`
- Перейдите на сайт по адресу [http://127.0.0.1:8000](http://127.0.0.1:8000).


### Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).
