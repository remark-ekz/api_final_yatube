# API для проекта YATUBE - Социльный блог для размещения постов в сети

Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
### Запуск проекта
Чтобы локально развернуть проект необходимо:

1. Клонировать репозиторий:
```bash
https://github.com/remark-ekz/api_final_yatube.git
```

2. Создать виртуальное окружение:
```bash
python -m venv venv
```

3. Активировать виртуальное окружение:
```bash
source venv\Scripts\activate
```

4. Обновить pip и установить зависимости из ```requirements.txt```:
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

5. Выполнить миграции и запустить проект:
```bash
python manage.py migrate
python manage.py runserver
```
6. Ввести в браузере ```http://127.0.0.1:8000/redoc``` и ознакомиться с более подробной документацией к API.