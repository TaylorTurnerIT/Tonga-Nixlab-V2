# Tonga Homelab
This project is a purely declarative configuration designed to create NixOS virtual machines using OpenTofu. The majority of services that will run on this system will be Podman Quadlets with a focus on security.

## Security
Security is enforced using a multi-layered defense system. 
1. Tailscale-enforced internal containers
2. Proxied connection to my home network

## Virtual Machines
Containers will be hosted exclusively through NixOS Virtual Machines. 
The planned Virtual Machines and Containers include:
1. **Private Containers**
    - [Caddy](https://github.com/caddyserver/caddy) ❌
    - [Gitea](https://github.com/go-gitea/gitea) ❌
    - Observability Suite ([Grafana](https://github.com/grafana/grafana), [Loki](https://github.com/grafana/loki), [Prometheus](https://github.com/prometheus)) ❌ 
    - [Home-Assistant](https://github.com/home-assistant/core) ❌
    - [MinIO S3](https://github.com/minio/minio) ❌
    - [Huginn](https://github.com/huginn/huginn) ❌ 
    - *Arr Suite ([Radarr](https://github.com/Radarr/Radarr), [Seerr](https://github.com/seerr-team/seerr), [Sonarr](https://github.com/Sonarr/Sonarr), [Prowlarr](https://github.com/Prowlarr/Prowlarr), [Bookshelf](https://github.com/bookshelf/bookshelf), [qBitTorrent](https://github.com/qbittorrent/qBittorrent)) ❌
    - [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) ❌
    - [Authentik](https://goauthentik.io/) ❌
    - [Gaia](https://github.com/gaia-app/gaia) ❌
    - [Docker Mailserver](https://github.com/docker-mailserver/docker-mailserver) ❌
2. **Public Containers**
    - [Jellyfin](https://github.com/jellyfin/jellyfin) ❌
    - [Vaultwarden](https://github.com/dani-garcia/vaultwarden) ❌
    - [Homepage](https://github.com/prometheus) ❌
    - [Bar Assistant](https://github.com/karlomikus/bar-assistant) ❌
    - [Homebox](https://github.com/sysadminsmedia/homebox) ❌
    - [Immich](https://github.com/immich-app/immich) ❌
    - [JupyterLab](https://github.com/jupyterlab/jupyterlab) ❌
    - [Pterodacytl](https://github.com/pterodactyl/panel) ❌