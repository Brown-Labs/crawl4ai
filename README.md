# crawl4ai

AI-powered web crawler API.

## Quick Start

```bash
git clone git@github.com:Brown-Labs/crawl4ai.git
cd crawl4ai
./setup.sh
docker compose up -d
```

## Environment Variables

Copy `.env.example` to `.env` and fill in your values:

```bash
cp .env.example .env
```



## Auto Deploy

Push to `main` to trigger automatic deployment via GitHub Actions.

## Image Updates

A weekly GitHub Action checks for new Docker image versions and opens an issue when updates are available.
