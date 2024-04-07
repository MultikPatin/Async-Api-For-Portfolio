![repo size](https://img.shields.io/github/repo-size/foxygen-d/cat_charity_fund)
![py version](https://img.shields.io/pypi/pyversions/3)
-----
[![Python](https://img.shields.io/badge/Python-3.9|3.10|3.11-blue?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![pydantic](https://img.shields.io/badge/pydantic-2.6.3-blue?style=flat&logo=python&logoColor=white)](https://pypi.org/project/pydantic/2.6.3/)
[![psycopg2](https://img.shields.io/badge/psycopg2-2.9.9-blue?style=flat&logo=python&logoColor=white)](https://pypi.org/project/psycopg2/2.9.9/)
[![backoff](https://img.shields.io/badge/backoff-2.2.1-blue?style=flat&logo=python&logoColor=white)](https://pypi.org/project/backoff/2.2.1/)
[![elasticsearch](https://img.shields.io/badge/elasticsearch-8.12.1-blue?style=flat&logo=python&logoColor=white)](https://pypi.org/project/elasticsearch/8.12.1/)
---
[![Poetry](https://img.shields.io/badge/Poetry-used-green?style=flat&logo=python&logoColor=white)](https://pypi.org/project/poetry/)
[![Ruff](https://img.shields.io/badge/Ruff-used-green?style=flat&logo=python&logoColor=white)](https://pypi.org/project/ruff/)
[![Mypy](https://img.shields.io/badge/Mypy-used-green?style=flat&logo=python&logoColor=white)](https://pypi.org/project/mypy/)


# Async-Api-For-Portfolio
Сервис асинхронного api для высоконагруженной системы 

## Описание

Сервис реализует ETL-пайплайн для переноса данных из Postgres в Elastic


## Инструкция по развёртыванию проекта

* клонировать проект на компьютер
    ```bash
    git clone git@github.com:MultikPatin/Async-Api-For-Portfolio.git
    ```
* Установить менеджер зависимостей poetry
    ```bash
    python -m pip install poetry
    ```
* запуск виртуального окружения
    ```bash
    poetry shell
    ```
* установить зависимости
    ```bash
    poetry install --all-extras --with dev --with test
    ```
Сервис реализован в контейнерах Docker  

* запуск docker-compose
    ```bash
    docker-compose up -d -f docker-compose.local.yml
    ```
Для выполнения тестов в контейнерах Docker  

* запуск docker-compose
    ```bash
    docker-compose up -d -f docker-compose.test.yml
    ```
