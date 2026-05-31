# Loved

## Visão Geral

Aplicação Next.js em evolução com página web, endpoint de status, PostgreSQL em Docker e teste de integração.

## Problema Resolvido

Constrói uma base full-stack incremental com observabilidade mínima do banco por meio de `/api/v1/status`.

## Stack

JavaScript, Next.js, React, PostgreSQL, Docker Compose, Jest

## Arquitetura

`pages/`: interface e rotas API; `infra/database.js`: conexão PostgreSQL; `infra/compose.yaml`: serviço local; `tests/`: integração.

Consulte o [diagrama de arquitetura](../../assets/diagrams/architecture.mmd).

## Instalação

```bash
npm install
Copy-Item .env.example .env.development
```

## Execução Local

```bash
npm run dev
```

## Variáveis de Ambiente Esperadas

POSTGRES_HOST, POSTGRES_PORT, POSTGRES_USER, POSTGRES_PASSWORD, POSTGRES_DB, DATABASE_URL, POSTGRES_CA

Use [.env.example](../../.env.example) apenas como referência e nunca versione valores reais.

## Estrutura de Pastas

`pages/`: interface e rotas API; `infra/database.js`: conexão PostgreSQL; `infra/compose.yaml`: serviço local; `tests/`: integração.

## Screenshots

Adicione capturas revisadas em [assets/screenshots/](../../assets/screenshots/) sem dados sensíveis.

## Limitações

O repositório já rastreia `.env.development`. Este PR não altera esse arquivo; revise e rotacione qualquer valor real separadamente.

## Próximos Passos

Consulte o [roadmap](../../ROADMAP.md).

## Segurança e Contribuição

Leia [SECURITY.md](../../SECURITY.md) e [CONTRIBUTING.md](../../CONTRIBUTING.md).
