# AI Personal Assistant Project Context

## Project Goal
An AI Personal Assistant that integrates email/calendar workflows using Nylas and applies intelligence via OpenAI API.

## Tech Stack
- Python 3.13+ (Managed by uv)
- FastAPI
- PostgreSQL (SQLAlchemy)
- Docker & Docker Compose
- Nylas API v3

## Development Standards
- Always verify environment variables through `.env` configurations.
- Separate routes, models, and schemas clearly inside `src/`.
- Ensure tests are structured neatly in `tests/`.
