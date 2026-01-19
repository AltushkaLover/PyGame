✨ Особенности

🎮 Геймификация обучения

· 35+ уроков от начального до экспертного уровня
· Система опыта (XP) за выполнение заданий
· Уровни с повышением за набранный опыт
· Достижения за учебные подвиги

📊 Отслеживание прогресса

· Детальная статистика по пройденным урокам
· Визуализация прогресса по уровням сложности
· История активности за все время

🚀 Быстрый старт

Установка за 5 минут

Bash

# 1. Клонируйте репозиторий
git clone [https://github.com/yourusername/python-master.git](https://github.com/AltushkaLover/PyGame)
cd python-master

# 2. Создайте виртуальное окружение (опционально)
python -m venv venv
# Для Windows:
venv\Scripts\activate
# Для Mac/Linux:
source venv/bin/activate

# 3. Установите зависимости
pip install -r requirements.txt

# 4. Запустите приложение
python app.py

# 5. Откройте в браузере
# http://localhost:5000
Минимальные требования

· Python 3.8 или выше
· Любой современный браузер
· 100 МБ свободного места

📚 Структура проекта

python-master
├── app.py              # Основное Flask-приложение
├── python_game.db      # База данных SQLite
├── templates/          # HTML шаблоны
│   ├── base.html      # Основной шаблон
│   ├── index.html     # Главная страница
│   ├── login.html     # Страница входа
│   ├── register.html  # Страница регистрации
│   ├── dashboard.html # Личный кабинет
│   ├── lesson.html    # Страница урока
│   ├── practice.html  # Практика с кодом
│   ├── achievements.html # Достижения
│   └── profile.html   # Профиль пользователя
