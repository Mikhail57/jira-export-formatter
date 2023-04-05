# Форматтер для выгрузки из жиры в Excel

0. Установить зависимости `pip intall -r requirements.txt`
1. Залогиниться в жиру, скопировать `Cookie`
2. Создать `.env` файл из семпла: `cp .env.sample .env`
3. Заполнить `URL` как `https://<сервер жиры>/rest/api/2/search`
4. Заполнить `USER` своим юзернеймом
5. Заполнить `COOKIE` значением из п.2
6. Запустить скрипт `python main.py [YYYY-MM-DD]`, опционально указав начало периода

Заценить `output/report.xlsx`
