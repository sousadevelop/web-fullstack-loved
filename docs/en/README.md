# Loved

## Overview

Evolving Next.js application with a web page, status endpoint, Docker-based PostgreSQL, and an integration test.

## Purpose

This technical portfolio project documents the implemented workflow and its current boundaries without changing application behavior.

## Stack

JavaScript, Next.js, React, PostgreSQL, Docker Compose, Jest

## Architecture

The repository keeps its existing application structure. Use the architecture diagram as the entry point for understanding the implemented components.

See the [architecture diagram](../../assets/diagrams/architecture.mmd).

## Installation

```bash
npm install
Copy-Item .env.example .env.development
```

## Local Run

```bash
npm run dev
```

## Expected Environment Variables

POSTGRES_HOST, POSTGRES_PORT, POSTGRES_USER, POSTGRES_PASSWORD, POSTGRES_DB, DATABASE_URL, POSTGRES_CA

Use [.env.example](../../.env.example) as a placeholder reference only.

## Folder Structure

The repository keeps its existing application structure. Use the architecture diagram as the entry point for understanding the implemented components.

## Screenshots

Reviewed screenshots belong in [assets/screenshots/](../../assets/screenshots/).

## Limitations

This is an educational portfolio project. Review the security notes and roadmap before considering deployment.

## Next Steps

See the [roadmap](../../ROADMAP.md).

## Security and Contributing

Read [SECURITY.md](../../SECURITY.md) and [CONTRIBUTING.md](../../CONTRIBUTING.md).
