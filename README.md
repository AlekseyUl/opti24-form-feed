# Opti24 Form Feed

## Описание
Тестовое задание для компании **opti24**: создание сайта с двумя страницами.

1. **Форма отправки**:  
   - Поля: Email, Имя  
   - Кнопка "Кликнуть" для отправки данных на сервер  
   - Сохранение данных в базу данных  
   - Перенаправление на страницу ленты после отправки  

2. **Страница ленты**:  
   - Список пользователей с именем, email, датой последней отправки  
   - Подсчёт общего числа отправок для каждого пользователя (группировка по email)  

## Установка и запуск
1. Клонируйте репозиторий:  
   ```bash
   git clone https://github.com/your-username/opti24-form-feed.git
   cd opti24-form-feed```
2. Настройте базу данных в MySQL:
```CREATE DATABASE form_project CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
USE form_project;
CREATE TABLE submissions (
    id INT AUTO_INCREMENT PRIMARY KEY,
    email VARCHAR(255) NOT NULL,
    name VARCHAR(255) NOT NULL,
    created_at DATETIME NOT NULL
);```


   
