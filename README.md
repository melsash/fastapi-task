# FastAPI Tasks Project

CRUD сервис для управления задачами (уровень "Студент").

## Стек
- FastAPI
- PostgreSQL
- SQLAlchemy + Alembic
- Docker + Docker Compose

## Установка и запуск
```bash
git clone https://github.com/ТВОЙ_НИК/fastapi-tasks.git
cd fastapi-tasks

# Запуск базы данных
docker-compose up -d

# Запуск сервера
uvicorn app.main:app --reload





Эндпоинты

POST /tasks — создать задачу

GET /tasks — список задач (поддерживает фильтрацию по status)

GET /tasks/{id} — получить задачу

PUT /tasks/{id} — обновить задачу

DELETE /tasks/{id} — удалить задачу




После запуска сервер доступен на
 http://127.0.0.1:8000/docs