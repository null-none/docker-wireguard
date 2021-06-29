# docker-wireguard

WireGuard is designed as a general purpose VPN for running on embedded interfaces and super computers alike, fit for many different circumstances.

##### Config .env file
```bash
IMAGE=linuxserver/wireguard
PUID=1000
PGID=1000
TZ=Asia/Hong_Kong
SERVERURL=1.2.3.4
SERVERPORT=51820
INTERNAL_SUBNET=10.0.0.0
```

##### Run docker container
```bash
docker-compose up
```