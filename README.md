## Чат на Websocket

Заходим в каталог .

* `server.js` - серверная часть, слушает TCP порт 80 (ждет подключений);
* `client.js` - клиентская часть, подключается к `127.0.0.1` на порт `80`.

## Задания

1. Добавить формат сериализации в ретранслятор, например JSON
2. Добавить имя пользователя и/или аутентификацию
3. Реализовать историю чата (n сообщений или m минут) для вновь подключившихся
4. Обернуть ретранслятор в EventEmitter на стороне клиента
5. Сохранять сообщения на диск или в базу данных (например MongoDB)
6. Загружать историю при перезапуске серверного приложения
7. Добавить комнаты в чат или сделать личные сообщения

