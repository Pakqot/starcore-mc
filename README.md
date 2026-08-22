# starcore

**STARCORE** is a public reference implementation of the hosting architecture
used at **Suncore** — a game server hosting company — scaled down to a
single, professionally operated Minecraft server. Infrastructure as Code
(Ansible + Kubernetes), remotely manageable end-to-end via a Telegram bot.

## Status

🚧 Work in progress — see commit history for details.

## Progress

- [x] Base OS: Debian 13 (trixie), LVM-partitioned disk
- [x] SSH: key-only authentication, password login disabled, root login disabled
- [ ] WireGuard remote access
- [ ] Firewall (nftables)
- [ ] Storage layout (zram swap, service data isolation)
- [ ] Docker
- [ ] k3s (single-node Kubernetes)
- [ ] Power management (24/7 operation)
- [ ] Monitoring (Prometheus/Grafana/Alertmanager → Telegram)
- [ ] Minecraft server
- [ ] Telegram control bot
- [ ] CI/CD

## Architecture

_TODO — added once the core services are in place_

## Stack

_TODO_

## Repository structure

Will grow into `k8s/`, `telegram-bot/`, `docs/` as later stages land.

## Getting started

_TODO_

## License

MIT — see [LICENSE](LICENSE)