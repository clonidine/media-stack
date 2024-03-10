## Stack
- **Jellyfin**
- **Jackett**
- **Radarr**
- **Flaresolverr**
- **qBittorrent**

## Requirements
- **Docker (25.0.2 tested version)**
- **Docker compose (2.24.5 tested version)**

## How to run
- `git clone https://github.com/clonidine/media-stack.git`
- `cd media-stack`
- `docker-compose up -d`
- `docker exec -it radarr chown 1000:1000 movies downloads`