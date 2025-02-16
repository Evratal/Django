# Skystore

Skystore - это веб-приложение для хранения и управления плагинами и примерами кода. Оно включает в себя каталог с различными ресурсами и страницу с контактной информацией.

## Установка и настройка

### Предварительные требования

- Python 3.12 
- Django 5.1 
- pip (Python package installer)

### Шаги установки

1. **Клонируйте репозиторий**
```bash 
git clone https://github.com/Evratal/skystore.git cd skystore
```

2. **Создайте и активируйте виртуальное окружение**

```bash 
python -m venv venv # Для Windows: venv\Scripts\activate # Для macOS/Linux: source venv/bin/activate
```

3. **Установите необходимые зависимости**
```bash 
pip install -r requirements.txt
```
4. **Настройте базу данных**
```bash 
python manage.py migrate
```
5. **Запустите сервер разработки**
```bash 
python manage.py runserver
```
6. **Откройте браузер и перейдите по следующему адресу:**
http://127.0.0.1:8000/ ```