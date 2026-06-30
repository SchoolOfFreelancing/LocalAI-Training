# LocalAI Hands-on Training Module

A hands-on Training covering LocalAI fundamentals, production deployment, and building a profitable service around it.

## Prerequisites
- Linux fundamentals (CLI, SSH, package management)
- Basic networking (DNS, ports, firewalls)
- Docker basics
- A VPS or cloud account (DigitalOcean/AWS/Linode), GPU optional
- Upwork freelancer account (for Day 5)

## Schedule

### Day 1 — LocalAI Fundamentals
- What is LocalAI, architecture overview, supported model backends
- Installation via Docker/binary on Linux
- Configuration files (models.yaml, .env) and directory structure
- Loading models (LLM, embeddings, image, audio)
- **Lab:** Install LocalAI and run your first inference request

### Day 2 — Domain & Networking Setup
- Buying/configuring a domain (registrar, DNS records)
- Pointing A/CNAME records to your server
- Setting up subdomains for LocalAI API endpoints
- Reverse proxy basics (Nginx/Caddy) + API key protection
- **Lab:** Map a custom domain to your LocalAI instance

### Day 3 — Production Deployment
- Hardening the VPS (firewall, SSH keys, fail2ban)
- SSL/TLS via Let's Encrypt/Certbot
- Container orchestration (Docker Compose/systemd)
- GPU passthrough and resource limits
- Logging, monitoring, and backups
- **Lab:** Deploy LocalAI to production with HTTPS

### Day 4 — Scaling & Troubleshooting
- Model performance tuning (quantization, context size, threads)
- Common errors and debugging workflow
- Update/rollback strategy for models and the LocalAI binary
- Security best practices (rate limiting, auth, API key rotation)
- **Lab:** Simulate and resolve 3 common production issues

### Day 5 — Upwork Marketplace Service Development
- Identifying LocalAI service niches (self-hosted AI setup, migration, support)
- Writing a compelling Upwork gig title & description
- Pricing models (fixed-price vs hourly, packages)
- Portfolio/proof-of-work prep using Day 1–4 labs
- Client communication and proposal templates
- **Lab:** Publish a live Upwork gig for LocalAI services

## Outcomes
By the end of this Training, participants will:
- Deploy LocalAI to a production server with a custom domain and SSL
- Troubleshoot and maintain a live LocalAI instance
- Have a published, client-ready Upwork service listing

## Resources
- `/configs` — sample config files used in labs
- `/scripts` — setup and deployment scripts
- `/templates` — Upwork gig and proposal templates

# Disclaimer
This repository is intended to provide guidance, documentation, and support resources related to LocalAI installation. Product names, trademarks, and service names belong to their respective owners.

⭐ If this repository helps you, please consider starring it and sharing it with others.
