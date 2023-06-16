<div align="center">
  <img alt="celery-with-fastapi" height="100px" width="100px" src="logo.png" />
  <h1>Trigger a task with FastAPI, Celery</h1>
</div>

<p align="center">
  <a href="https://docs.celeryq.dev/en/stable/getting-started/introduction.html">
    <img src="https://img.shields.io/badge/Awesome-Celery-informational?style=for-the-badge&logo=awesomelists&labelColor=17202A&color=1abc9c&logoColor=1abc9c" alt="Awesome">
  </a>
</p>

## Table of Contents

- [Up and Run](#up-and-run)
- [Trigger a task](#trigger-a-task)

### Up and Run

```sh
git clone https://github.com/shahnawaz-pabon/celery-with-fastapi.git
cd celery-with-fastapi
docker-compose up --build
```

### Trigger a task

Open a terminal and trigger a new task

```sh
curl http://localhost:8001/tasks -H "Content-Type: application/json" --data '{"type": 0}'
```
