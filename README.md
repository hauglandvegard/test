# test

## Prerequisites

[Install uv](https://docs.astral.sh/uv/getting-started/installation/)

## Setup

```bash
uv sync --group dev
cp .env.example .env
```

## Run

```bash
uv run python -m src.main
```

## Dev

```bash
uv run ruff format .
uv run ruff check .
uv run mypy src
uv run pytest
```
