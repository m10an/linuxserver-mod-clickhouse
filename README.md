# ClickHouse - Docker mod for linuxserver

This mod adds a clickhouse-client, to be installed/updated during container start.

By default it installs latest version, you can specify version using environment variable `CLICKHOUSE_VERSION`

```yaml
- DOCKER_MODS=ghcr.io/m10an/linuxserver-mod-clickhouse:latest
- CLICKHOUSE_VERSION=21.12.2.17
```
