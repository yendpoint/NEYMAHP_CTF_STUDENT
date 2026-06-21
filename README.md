# NEYMAHP_CTF_STUDENT

Docker Compose-based CTF environment for Neymahp CTF.

## Quick Start

1. Clone the repository.
2. Run:
   ```bash
   docker compose up -d
   ```
3. Open the portal at `http://localhost:8080/neymahp/`.

## Included services

- `apache` — reverse proxy and public entry point
- `web` — Django application backend
- `litellm-db` — PostgreSQL database for the AI service
- `litellm` — internal assistant service
- `litellm-seed` — one-time seeding job

No Docker login is required for the prebuilt public images.
