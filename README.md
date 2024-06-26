# caddy-docker-proxy-cloudflare

A custom Caddy build with the [Caddy Docker Proxy](https://github.com/lucaslorentz/caddy-docker-proxy) and [Cloudflare](https://github.com/caddy-dns/cloudflare) modules installed.

Published on the GitHub Container Registry.

This is mostly for personal use, and it does not update automatically when new releases of Caddy or the modules come out.

## Releasing a new version
1. Edit `CADDY_VERSION` in `Dockerfile`
2. `git add Dockerfile`
3. `git commit -m "feat: caddy version <version>"`
4. `git tag -a <version> -m "Release <version>"`
5. `git push`
6. `git push --tags`
