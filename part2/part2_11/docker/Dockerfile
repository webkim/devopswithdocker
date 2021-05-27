
FROM tiangolo/uvicorn-gunicorn-fastapi:python3.7

RUN apt update

RUN apt install -y pipenv

RUN pipenv install fastapi uvicorn sqlalchemy alembic

RUN pipenv install python-dotenv

EXPOSE 80