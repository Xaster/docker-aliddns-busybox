# docker-aliddns-busybox
Docker: AliDDNS By aliyun-ddns-cli (Build in Debian / Based On BusyBox)

# Thanks
- https://github.com/chenhw2/aliyun-ddns-cli

# Usage
```
$ docker pull xaster/docker-aliddns-busybox

$ docker run -d \
    --name docker-aliddns-busybox \
    -e AKID=YOUR_ACCESS_KEY_ID \
    -e AKSCT=YOUR_ACCESS_KEY_SECRET \
    -e DOMAIN=YOUR_DOMAIN \
    -e REDO=600 \
    -e TIMEZONE=YOUR_TIME_ZONE \
    xaster/docker-aliddns-busybox
```
