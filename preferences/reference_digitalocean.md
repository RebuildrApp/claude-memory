---
name: DigitalOcean CLI setup
description: How to connect to DigitalOcean via doctl CLI — install location, auth steps, and usage context
type: reference
---

## DigitalOcean CLI (doctl)

- **Binary location:** `~/.local/bin/doctl` (v1.154.0)
- **Auth command:** `doctl auth init` (prompts for API token)
- **API token creation:** https://cloud.digitalocean.com/account/api/tokens
- **User preference:** DigitalOcean is the preferred cloud provider for all apps — databases, App Platform, etc.

## Common doctl commands

- `doctl apps list` — list App Platform apps
- `doctl apps create --spec <spec.yaml>` — deploy an app
- `doctl databases list` — list managed databases
- `doctl databases create <name> --engine <pg|mysql|redis|mongodb>` — create a database
- `doctl compute droplet list` — list droplets
- `doctl registry login` — authenticate Docker to DO container registry
