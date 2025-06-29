# 🫂Анонимные знакомства в Telegram

Телеграм бот для знакомств, который соединяет двух случайных пользователей в приватном чате. Идеальное решение для тех, кто хочет найти новых друзей или вторую половинку в уютной атмосфере.

## ✨ Ключевые функции

- 🧑‍🤝‍🧑 **Соединение 1 на 1** - Анонимный чат между двумя пользователями
- 🔍 **Фильтр по полу** - Поиск только мужчин, женщин или без предпочтений
- 📝 **Редактируемый профиль** - Возможность настройки своей анкеты
- 💡 **Подсказки для общения** - Команда `/help` предложит темы для разговора
- 🔄 **Смена собеседника** - В любой момент можно начать новый диалог

Есть возможность поддержать проект донатом

## 🛠 Быстрая настройка

### 1. Создание виртуального окружения
```bash
python -m venv venv
source venv/bin/activate  # Для Linux/MacOS
venv\Scripts\activate    # Для Windows
```

### 2. Установка зависимостей
```bash
pip install -r requirements.txt
```

### 3. Настройка конфигурации
Создайте файл `.env` с путем до ваше базы данных, API токеном телеграмма и вашем айди:
```ini
DB_PATH=путь_к_бд
TG_TOKEN=ваш_токен_бота
ADMIN_ID=айди_вашего_аккаунта
```

### 4. Персонализация
1. В файле `config.py` замените ссылку на донат (в примере ипользуется сервис cloudTips):
```python
DONATE_URL = "https://ваша_ссылка_на_донат"
```

2. Замените изображение `donate.jpg` (в примере используется изображение qr кода с сервиса cloudTips) в папке `images` на свое (сохранив название файла)

## 🚀 Запуск бота
```bash
python main.py
```
