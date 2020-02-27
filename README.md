# SManager
 SManager

Система внутреннего обмена документами. Позволяет делиться документами, их шаблонами и переписываться внутри сети.

### Настройка внутри сети

1) Создать mysql db запустив файл workflowDB.sql
2) Указать актуальные пути к db в config файле 
3) Указать актуальные настойки базы данных в config файле Server/workflow_server/bin/Debug/dbConfig.txt (Адрес;Порт;Название БД;Пользователь;Пароль)
5) Запустить сервер (Server/workflow_server/bin/Debug/workflow_server.exe), клиентское приложение (Client/workflow/bin/Debug/workflow.exe)
