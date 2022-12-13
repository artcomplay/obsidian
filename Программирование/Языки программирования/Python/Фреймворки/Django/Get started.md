[[Django]]
1) Создание виртуальной среды в папке с проектами
py -m venv myproject

2) Активация виртуальной среды с помощью запуска файла activate.bat по пути
myproject / Scripts / activate.bat

3) Переход в папку с проектом
cd myproject

4) Выполнение команды в виртуальной среде для создания проекта
django-admin startproject notebase

5) Запуск проекта
py manage.py runserver




py -m venv django4
django4 / Scripts / activate.bat
cd django4
django-admin startproject notebase
cd notebase
py manage.py runserver