# TODO-приложение

Простое веб-приложение для списка задач на Flask + SQLite.

## Возможности
- Добавление задач через форму
- Отображение списка задач
- Удаление задач

## Технологии
- Python 3
- Flask
- SQLite
- Gunicorn

## Локальный запуск
```bash
pip install -r requirements.txt
python app.py
```

Откройте `http://127.0.0.1:5000/` в браузере.

## Деплой на Render
1. Загрузите проект в репозиторий GitHub.
2. На Render создайте новый Web Service, подключите репозиторий.
3. Start Command: `gunicorn app:app`
4. Нажмите Deploy.