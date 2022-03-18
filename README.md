# cdp-example
This is an example demonstrating how to use caddy-docker-proxy
---

## Features
* [caddy-docker-proxy](https://github.com/lucaslorentz/caddy-docker-proxy#caddy-docker-proxy) which is a plugin to [Caddy2](https://caddyserver.com/docs/) that enhances its reverse-proxy capablities
* A small static, "web app" that runs on [Apache](https://hub.docker.com/_/httpd), developed using [VueJs 2](https://v2.vuejs.org/v2/guide/index.html) than consumes an Api.
* A simple, dockerized api (created by me), developed as a microservice to [generate QrCodes](https://github.com/raonigabriel/spring-qrcode-example#spring-boot-qrcode-example)
* Custom host names, using [local.gd](https://local.gd/), which is an alternative to [nip.io](https://nip.io/)


## Usage
```
docker compose up -d
```

Then, point your browser to [http://apache.local.gd/](http://apache.local.gd/). It will **NOT** access the internet, but your localhost instead.

How cool is that? Please, add a ⭐.
