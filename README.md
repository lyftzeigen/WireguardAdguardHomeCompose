# WireguardAdguardHomeCompose

This is docker compose config for wireguard and adguardhome installation.

1. Clone this repo on server
2. Run `docker-compose up -d`
3. Configure **adguardhome** via the web interface on **3000** port
4. Don't forget to hide exposing **80** and **3000** ports
5. Run `docker-compose up -d` again

All wireguard config files stored in ./wireguard/config
