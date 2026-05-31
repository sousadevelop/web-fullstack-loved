# Loved

## Descripción general

Aplicación Next.js en evolución con página web, endpoint de estado, PostgreSQL en Docker y prueba de integración.

## Objetivo

Este proyecto de portafolio técnico documenta el flujo implementado y sus límites actuales sin modificar el comportamiento de la aplicación.

## Stack

JavaScript, Next.js, React, PostgreSQL, Docker Compose, Jest

## Arquitectura

El repositorio conserva su estructura de aplicación existente. Use el diagrama de arquitectura como punto de entrada para comprender los componentes implementados.

See the [architecture diagram](../../assets/diagrams/architecture.mmd).

## Instalación

```bash
npm install
Copy-Item .env.example .env.development
```

## Ejecución local

```bash
npm run dev
```

## Variables de entorno esperadas

POSTGRES_HOST, POSTGRES_PORT, POSTGRES_USER, POSTGRES_PASSWORD, POSTGRES_DB, DATABASE_URL, POSTGRES_CA

Use [.env.example](../../.env.example) as a placeholder reference only.

## Estructura de carpetas

El repositorio conserva su estructura de aplicación existente. Use el diagrama de arquitectura como punto de entrada para comprender los componentes implementados.

## Capturas de pantalla

Reviewed screenshots belong in [assets/screenshots/](../../assets/screenshots/).

## Limitaciones

Este es un proyecto educativo de portafolio. Revise las notas de seguridad y el roadmap antes de considerar un despliegue.

## Próximos pasos

See the [roadmap](../../ROADMAP.md).

## Seguridad y contribución

Read [SECURITY.md](../../SECURITY.md) and [CONTRIBUTING.md](../../CONTRIBUTING.md).
