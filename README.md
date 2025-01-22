# Coursework_DRF

## Установка:
1. Клонировать репозиторий:

```
https://github.com/AleksandrIlin/Coursework_DRF
```

2. Установка зависимостей:

```
poetry install
```

3. Задачи проекта:

```
В рамках учебного курсового проекта реализация бэкенд-части SPA веб-приложения.
```

4. Тесты:

```
python manage.py test
coverage run --source='.' manage.py test
coverage report
тестами покрыто 82%
```

5. Запуск проекта: 

```
python manage.py runserver
```

6. Контейнеризация с Docker

   I. Убедитесь, что у Вас установлен Docker и Docker Compose.

   II. Для сборки и запуска проекта в контейнерах выполните:

```
docker-compose up -d --build
```
``
    III. Для остановки контейнеров выполните:

```
docker-compose down
```
7. CI/CD с GitHub Actions
Убедитесь, что Ваш проект настроен для работы с GitHub Actions.

При каждом пуше в репозиторий будут запускаться тесты и линтинг кода, а также проверяться возможность сборки Docker-образов.

В случае успешных проверок проект будет автоматически развернут на удаленном сервере.

Запуск проекта на удаленном сервере
Убедитесь, что сервер готов к работе с Docker и Docker Compose.

Настройте SSH-доступ к серверу для деплоя через GitHub Actions.

Проект будет автоматически разворачиваться на сервере при каждом успешном пуше в репозиторий.

http://85.92.111.109/