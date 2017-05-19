# shadowsocks-server-docker

shadowsocks server(golang) for docker

## How to use

1. pull the docker repo
```bash
docker pull scofieldpeng/shadowsocks-server:0.1
```

2. docker run
```bash
docker run --name ss-server -p local_port:container_port scofieldpeng/shadowsocks-server:0.1 -p PORT -p PASSWORD -m METHOD -t TIMEOUT
```
the config is same as the shadowsocks-go, more detail see: [https://github.com/shadowsocks/shadowsocks-go](https://github.com/shadowsocks/shadowsocks-go)

