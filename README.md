# n8n on Render (deploy config)

This repository contains a minimal `render.yaml` for deploying n8n on Render.
- Do NOT store secrets in this repo.
- Set DATABASE_URL, N8N_ENCRYPTION_KEY and other secrets in Render Dashboard (Environment).
- Pin the image tag in render.yaml to control updates (change tag only when you want to upgrade).