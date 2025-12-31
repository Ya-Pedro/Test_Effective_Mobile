# Тестовое задание на позицию DevOps
Для запуска веб приложения неоходимо ввести команду "docker compose up --build" в директории с проектом

Для проверки результата можно выполниьб запрос в браузере: перейти по ссылке http://localhost или в командной строке выполнить curl http://localhost. В первом и второй варианте должно выдать ""Hello from Effective Mobile!""

# Структура репозитория

```text
backend/                   # Приложение
nginx/                     # Прокси
docker-compose.yml         # Запуск проекта
README.md                  # Документация
```

# Схема проекта

Браузер/терминал > nginx:80 > backend:8080
http://localhost
curl http://localhost
