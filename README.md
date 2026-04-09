# anythingllm

> Click To Deploy AnythingLLM — The all-in-one AI app for your docs

[![Sync](https://github.com/opensaasapps/anythingllm/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/anythingllm/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/anythingllm/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/anythingllm/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/anythingllm)](https://hub.docker.com/r/thefractionalpm/anythingllm)

Upstream: [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `STORAGE_DIR` | ⚪ | |
| `JWT_SECRET` | ✅ | |
| `LLM_PROVIDER` | ⚪ | |
| `OLLAMA_BASE_PATH` | ⚪ | |
| `EMBEDDING_ENGINE` | ⚪ | |
| `VECTOR_DB` | ⚪ | |
| `AUTH_TOKEN` | ✅ | |
| `SMTP_HOST` | ✅ | |
| `SMTP_PORT` | ⚪ | |
| `SMTP_SECURE` | ⚪ | |
| `SMTP_USER` | ✅ | |
| `SMTP_PASS` | ✅ | |
| `SMTP_FROM` | ⚪ | |

## Image

```
docker pull mintplexlabs/anythingllm:latest
docker pull thefractionalpm/anythingllm:latest
```

## Ports

| Port | Service |
|---|---|
| `3001` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
