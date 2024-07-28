[![GitHub Actions](https://github.com/SergeyZasimov7/kittygram_final/actions/workflows/kittygram_workflow.yml/badge.svg)](https://github.com/SergeyZasimov7/kittygram_final/actions)

Kittygram - это веб-приложение, созданное для любителей кошек, чтобы делиться своими фотографиями пушистых питомцев.  Пользователи могут:

Загружать фотографии своих кошек.
Добавлять описания к фотографиям.
Просматривать фотографии других пользователей.
Подписываться на других пользователей и следить за их обновлениями.
Оставлять комментарии к фотографиям.

### Стек технологий

Backend: Python (Flask), PostgreSQL
Frontend: HTML, CSS, JavaScript
Инфраструктура: Docker, GitHub Actions, Nginx 

### Как развернуть проект

1. Клонируйте репозиторий:
git clone https://github.com/SergeyZasimov7/kittygram_final


2. Создайте виртуальное окружение:
python3 -m venv venv
source venv/Scripts/activate


3. Установите зависимости:
pip install -r backend/requirements.txt


4. Заполните файл .env:
# PostgreSQL connection details
POSTGRES_DB=your_db
POSTGRES_USER=your_db_user
POSTGRES_PASSWORD=your_db_password
DB_NAME=your_db

# Secret key for Flask
SECRET_KEY=your_secret_key

5. В корневой папке выполнить следующую команду:
docker compose -f docker-compose.yml up -d 


### Автор

 - [Сергей Засимов](https://github.com/SergeyZasimov7)
