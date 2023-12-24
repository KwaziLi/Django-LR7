# Установка и запуск
1. Откройте командную строку в директории с mysite и requirements.txt.
2. `py -m venv env`
3. `pip install -r requirements.txt`
4. `py mysite/manage.py runserver`
5. В браузере откройте `127.0.0.1:8000`.

## Голосование
- `/polls/` - страница с голосованиями

## Аналитика
- `/analytics/` - графики результатов голосований
- `/analytics/questions` - вывод данных о голосованиях
- `/analytics/questions/<question_id>` - вывод данных о конкретном голосовании
- `/analytics/choices/` - вывод данных всех ответов на голосования
- `/analytics/choices/<question_id>` - вывод данных ответов на определенное голосование
