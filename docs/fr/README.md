# Loved

## Vue d'ensemble

Application Next.js en évolution avec page web, endpoint de statut, PostgreSQL via Docker et test d'intégration.

## Objectif

Ce projet de portfolio technique documente le flux implémenté et ses limites actuelles sans modifier le comportement de l'application.

## Stack

JavaScript, Next.js, React, PostgreSQL, Docker Compose, Jest

## Architecture

Le dépôt conserve sa structure applicative existante. Utilisez le diagramme d'architecture comme point d'entrée pour comprendre les composants implémentés.

See the [architecture diagram](../../assets/diagrams/architecture.mmd).

## Installation

```bash
npm install
Copy-Item .env.example .env.development
```

## Exécution locale

```bash
npm run dev
```

## Variables d'environnement attendues

POSTGRES_HOST, POSTGRES_PORT, POSTGRES_USER, POSTGRES_PASSWORD, POSTGRES_DB, DATABASE_URL, POSTGRES_CA

Use [.env.example](../../.env.example) as a placeholder reference only.

## Structure des dossiers

Le dépôt conserve sa structure applicative existante. Utilisez le diagramme d'architecture comme point d'entrée pour comprendre les composants implémentés.

## Captures d'écran

Reviewed screenshots belong in [assets/screenshots/](../../assets/screenshots/).

## Limites

Il s'agit d'un projet pédagogique de portfolio. Consultez les notes de sécurité et la roadmap avant d'envisager un déploiement.

## Prochaines étapes

See the [roadmap](../../ROADMAP.md).

## Sécurité et contribution

Read [SECURITY.md](../../SECURITY.md) and [CONTRIBUTING.md](../../CONTRIBUTING.md).
