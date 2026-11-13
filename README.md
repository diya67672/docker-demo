
# Docker Demo - FastAPI

## Project Description
This project creates a simple FastAPI application using Docker.

## Requirements
- Python
- Docker Desktop
- FastAPI
- Uvicorn

## Run the Project
Open the terminal in the project folder and run:

```bash
docker compose up --build
```

## Test API
Method: GET

URL: http://localhost:8000/health

Expected Response:

```json
{
  "status": "ok"
}
```

## Stop the Container

Press Ctrl + C and run:

```bash
docker compose down
```
