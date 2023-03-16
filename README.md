<p align="center">
    <img src="https://github.com/pymumu/smartdns/raw/master/doc/smartdns.png" width="150" />
</p>

<h1 align="center">SmartDNS</h1>

<p align="center">A local DNS server to obtain the fastest website IP for the best Internet experience.</p>

<p align="center">
    <a href="https://ghcr.io/dpooley/smartdns">Container Registry</a> ·
    <a href="https://github.com/pymumu/smartdns">Project Source</a>
</p>

<p align="center">
    <img src="https://img.shields.io/github/actions/workflow/status/dpooley/docker-smartdns/push.yml?branch=main" />
    <img src="https://img.shields.io/github/last-commit/dpooley/docker-smartdns" />
    <img src="https://img.shields.io/github/v/release/dpooley/docker-smartdns" />
    <img src="https://img.shields.io/github/release-date/dpooley/docker-smartdns" />
</p>

---

### Pull The Image

```bash
$ docker pull ghcr.io/dpooley/smartdns
```

### Start Container

```bash
$ docker run -d \
  -p 53:53/udp \
  -v /etc/smartdns/:/etc/smartdns/ \
  --restart=always \
  --name=smartdns \
  ghcr.io/dpooley/smartdns
```
