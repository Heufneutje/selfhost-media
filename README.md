# selfhost-media
The files I use for the media setup on my NAS/server.

Includes the following services:
- traefik for reverse-proxying different subdomains to specific containers
- dockersock-proxy to shield the docker socket from web-facing containers
- watchtower to keep containers updated automatically
- fail2ban to protect the Traefik dashboard from brute-force logins
- yacht for container management
- authelia for single sign-on with two-factor authentication
- sonarr for managing tv shows
- radarr for managing movies
- jackett for managing indexers
- qbittorrent for downloading
- handbrake for automatically transcoding media
- jellyfin as a media front-end
