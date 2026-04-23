# 🖥️ Hardened Home Lab Server — Raspberry Pi 5

A production-grade Ubuntu Server deployment on a Raspberry Pi 5, built from scratch with security-first principles.

## Stack

| Service | Purpose |
|---|---|
| Ubuntu Server 24.04 LTS | Operating system — headless, ARM architecture |
| SSH + ed25519 Key Auth | Secure remote access — password auth disabled |
| UFW Firewall | Default-deny policy — explicit port allowlist only |
| Docker | Container runtime for all services |
| Portainer | Visual Docker management dashboard |
| Pi-hole | Network-wide DNS filtering and ad blocking |
| Uptime Kuma | Real-time service health monitoring |
| Tailscale | Zero-trust VPN — secure remote access from anywhere |
| Nginx | Reverse proxy with self-signed SSL — HTTPS on port 443 |

## About

Built by Eric M as part of a career transition into cloud security and IT infrastructure.

- CompTIA Security+ certified
- Currently studying AZ-900 Azure Fundamentals
- LinkedIn: linkedin.com/in/ericmillertech
