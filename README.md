# toko-docker-dev

Local development Docker environment for Shop Application.

## Requirements
- Docker
- Docker Compose

## Setup
1. Copy `.env.example` to `.env`
2. Update `.env` with your credentials
3. Run: `docker compose up -d`

## Services
| Service | Port | Description |
|---------|------|-------------|
| MySQL 5.7 | 3306 | Shop Application database |

## Database
- Database name: `shop_application`
- Default user: `toko_user`