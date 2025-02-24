Copy world data to world_data -directory
Make sure the `WORLD_NAME` in `docker-compose.yml` correlates with the world data files added into the world_data -directory

Run this with `docker compose up -d`

In order to get this out from the host machine apply firewall rules:

```
sudo ufw allow 2456/udp
sudo ufw allow 2457/udp
sudo ufw allow 2458/udp
sudo ufw allow 27060/udp
```

Uses https://github.com/lloesche/valheim-server-docker
