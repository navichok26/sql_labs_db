# БД для лаб по СУБД

- `init.sql` - скрипт для создания таблиц и внесения в них тестовых данных
- `docker-compose.yml` - компоуз файл, с его помощью можно быстро в докере поднять БД с нужными табличками и данными


Поднимать командой: `docker-compose up -d`

После запуска postgresql заработает на localhost:6666, где в базе данных postgres будут все таблички из лабы.

- Пользователь: postgres
- Пароль: changeme
