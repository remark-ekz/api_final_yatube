API для проекта YATUBE - Социльный блог для размещения постов в сети

Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

https://github.com/remark-ekz/api_final_yatube.git

cd api_final_yatube

Cоздать и активировать виртуальное окружение:

python -m venv env
source venv/Scripts/activate

Установить зависимости из файла requirements.txt:

python -m pip install --upgrade pip
pip install -r requirements.txt

Выполнить миграции:

python manage.py migrate

Запустить проект:

python manage.py runserver