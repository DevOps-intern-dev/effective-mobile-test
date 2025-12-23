# Effective Mobile – Docker + Nginx Test Task

# Описание
  веб-приложение из двух сервисов:
 backend  HTTP-сервер на Python
  nginx  reverse proxy

Nginx принимает HTTP-запросы и проксирует их в backend-сервис.

---

# Запуск проекта

# Требования
 Docker
 Docker Compose

# Запуск

```bash
docker compose up --build -d
