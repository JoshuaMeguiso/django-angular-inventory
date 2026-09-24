# Django Angular Inventory

An inventory management application built with a Django REST API and an Angular frontend.

## Project structure

- `server/`: Django backend and REST API
- `client/`: Angular frontend
- `docs/`: Architecture, database, and API notes
- `docker/`: Development container definitions

## Backend development

```bash
cd server
source .venv/bin/activate
python manage.py runserver
```

The API is available at `http://127.0.0.1:8000/`.

## Status

The Django backend is scaffolded. The Angular client and API features will be added incrementally.
