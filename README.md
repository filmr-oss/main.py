# FastAPI Basic App

A beginner FastAPI project built with Python and Uvicorn.

## Features

- GET / — Returns a welcome message.
- GET /greet/{name} — Accepts a name and returns a personalized message.
- /docs — Interactive Swagger API documentation.

## Run the App

uvicorn main:app --reload

Open:

http://127.0.0.1:8000

Interactive API docs:

http://127.0.0.1:8000/docs

## Technologies

- Python
- FastAPI
- Uvicorn
