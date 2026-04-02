# Infrastructure Preferences

## Cloud Provider: DigitalOcean
- Use DigitalOcean for **all** deployments — no AWS, GCP, Azure
- Services used: App Platform, Managed Databases, Droplets, Container Registry

## Databases
- **Never use `defaultdb`** — always create a purpose-named database
- When setting up any app with a DO managed database, create a dedicated database before connecting the app

## CLI Tools
- `doctl` at `~/.local/bin/doctl` (v1.154.0)
- `gh` at `~/.local/bin/gh` (v2.89.0)
- Everything installed manually — no Homebrew on this machine

## Common doctl commands
- `doctl apps list` — list App Platform apps
- `doctl apps create --spec <spec.yaml>` — deploy an app
- `doctl databases list` — list managed databases
- `doctl databases create <name> --engine <pg|mysql|redis|mongodb>` — create a database
- `doctl compute droplet list` — list droplets
- `doctl registry login` — authenticate Docker to DO container registry
