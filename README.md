# caddy-docker

Custom docker image for [caddy web server](https://caddyserver.com/)

## Plugins included

```text
https://github.com/caddy-dns/cloudflare
https://github.com/mholt/caddy-ratelimit
```

## How to build

```text
docker build --no-cache --pull -t jakewmeyer/caddy-docker:2.6.2 .
docker push jakewmeyer/caddy-docker:2.6.2
```