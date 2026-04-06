# FastAPI POC Project

Simple API built with FastAPI and managed with uv.

## Requirements

* Python 3.12 (defined in `.python-version`)
* uv installed

## Setup

Clone the repository and install dependencies:

```bash
uv sync
```

This will:

* create `.venv`
* install all dependencies from `uv.lock`

## Run locally

```bash
uv run fastapi dev
```

## API Docs

Once running, open:

* http://127.0.0.1:8000/docs

## Notes

* Do not use `pip install` directly
* Use `uv add` to install new dependencies
* Always commit `uv.lock` after adding dependencies



# Next Steps:
Deploy this FastApi in a AWS Lambda and API Gateway, following this guide: https://youtu.be/U_d56hG7yEM?si=GU_aqRk_-BbxbMzd&t=494