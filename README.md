Тестовое задание:

Необходимо реализовать небольшой проект, который включает в себя 3 задачи.
Разместить код надо в публичном репозитории GitHub/GitLab.

Стек: strict TypeScript, postgres.js
Фреймворк на выбор: hono/elysia/fastify/express
Запрещено использовать: Nest, JWT, ORM
Таблицы в базе данных: users, products, purchases. Схему необходимо добавить в репозиторий.

Задача 1:
Сессии: регистрация, аутентификация, смена пароля

Задача 2:
Нужно отобразить массив объектов с двумя минимальными ценами на предмет (одна цена — tradable, другая — нет)
Получить данные можно через API: https://docs.skinport.com/items
Параметры app_id и currency — default
Postgres здесь использовать не нужно
В отдачу предметов необходимо добавить кэширование через Redis

Задача 3:
Нужно реализовать покупку выдуманного товара из таблицы products.
Таблицу надо заполнить самостоятельно (несколько предметов, цена должна быть float).
У пользователя должен быть баланс.
В ответе должен быть обновленный баланс пользователя.
