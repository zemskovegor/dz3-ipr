# дз-3 на 6 баллов
Приложение упаковано в Docker и запускается через Docker compose. Хранилище sqlite. Счетчик хранится в файле sqlite(counter_data), поэтому данные не пропадают при пересеоздании контейнера.
Перед запуском необходимо скопировать env.example в .env, где настроятся APP_PORT и GREETING,затем выполните docker compose up -d --build.
