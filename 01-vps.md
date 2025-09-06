# VPS padrão (Traefik + Portainer)

1. Acesse a VPS como **root** (`sudo -i`).
2. Atualize:
   ```bash
   apt-get update -y && apt-get upgrade -y && apt-get install -y curl ca-certificates
