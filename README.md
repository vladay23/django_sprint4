# django_sprint4
# Как запустить проект
Создание виртульной области  
python -m venv venv  
Активация  
venv\Scripts\activate  
Загрузка  
pip install -r requirements.txt  
Migrate  
python blogicum/manage.py migrate  
Пример бд  
python manage.py loaddata db.json  
Запуск сервера с http://127.0.0.1:8000/  
python manage.py runserver  
