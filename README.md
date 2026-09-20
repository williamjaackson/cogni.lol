# Cogni.lol

Turn PDFs into courses with AI summaries, lessons, quizzes and a study coach.

**Second place at the 2025 Tanda Hackathon.** Built by William Jackson, William Qu and Yiming He.

[![Cogni.lol homepage](docs/media/homepage.png)](docs/media/homepage.png)

## Run locally

Requires Docker and an Anthropic API key. Copy `.env.example` to `.env`, then fill in the database settings, `SECRET_KEY` and `ANTHROPIC_API_KEY`.

```sh
docker compose up --build
```

Open [localhost:8080](http://localhost:8080). React + TypeScript frontend, FastAPI backend and PostgreSQL.
