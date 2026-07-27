## Database & Backend Projects

| Project | Tech Stack | Description |
|---|---|---|
| [BuzzyHive 2.0](https://github.com/tttaufiqqq/Kelulut-Hive-Harvest-Readiness-Prediction) | ![Laravel](https://img.shields.io/badge/Laravel_13-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) ![Inertia.js](https://img.shields.io/badge/Inertia.js-9553E9?style=flat-square&logo=inertia&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![cPanel](https://img.shields.io/badge/Exabytes_cPanel-FF6C2C?style=flat-square&logo=cpanel&logoColor=white) | <ul><li>Final Year Project — IoT + ML system for kelulut (stingless bee) harvest readiness monitoring</li><li>ESP32 sensors push live data, KNN classifier predicts readiness, Telegram alerts beekeepers</li><li>Deployed via a GitHub Actions CI/CD pipeline (lint, deploy, deploy-ml stages)</li><li>Live at buzzyhive.urban-alert.com</li></ul> |
| [Animal Shelter Workshop](https://github.com/tttaufiqqq/Animal-Shelter-Workshop) | ![Laravel](https://img.shields.io/badge/Laravel_11-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![Livewire](https://img.shields.io/badge/Livewire-4E56A6?style=flat-square&logo=livewire&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) | <ul><li>Animal rescue and adoption platform with 5 databases across 3 engines (PostgreSQL, MySQL, MariaDB) on a Tailscale VPN mesh</li><li>Cross-database relationships enforced at the application layer</li><li>BITU3923 Workshop II</li></ul> |
| [BITD Workshop 2 Demo](https://github.com/tttaufiqqq/workshop-2-bitd-demo-project) | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) | <ul><li>Reference demo for BITU3923 students</li><li>Shows how to build a heterogeneous distributed database system across 3 engines and 3 machines connected via Tailscale</li></ul> |
| [Green Lifestyle Market](https://github.com/tttaufiqqq/green-lifestyle-market) | ![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black) ![Oracle](https://img.shields.io/badge/Oracle_23ai-F80000?style=flat-square&logo=oracle&logoColor=white) | <ul><li>Campus C2C marketplace for eco-friendly & pre-owned goods</li><li>Rebuilt from vanilla PHP/MySQL to Spring Boot + Oracle DB 23ai</li><li>Adds WebSocket, Flyway migrations & ToyyibPay payments</li></ul> |
| [Library System EDP](https://github.com/tttaufiqqq/Library-System-EDP) | ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET_4.7.2-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) | <ul><li>WinForms library management system for book, user and issue tracking with fine calculation</li><li>Built on Delegation + Repository + Template Method patterns</li></ul> |

---

## Infrastructure & Security Projects

| Project | Platform | Description |
|---|---|---|
| [Homelab: Database Fleet](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/01-oracle/oracle-install.md) | ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle_23ai-F80000?style=flat-square&logo=oracle&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | <ul><li>6 database engines, each on its own dedicated VM/LXC host across 13 machines on a single Proxmox node</li><li>Install, hardening, and troubleshooting logs for every engine's own quirks</li></ul> |
| [Homelab: Networking & Segmentation](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/18-network-segmentation/network-segmentation-execution.md) | ![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square) | <ul><li>Tailscale mesh VPN across the lab with a self-hosted split-horizon DNS layer (dnsmasq)</li><li>OPNsense router VM segmenting the fleet into 8 VLANs with per-VLAN DHCP and firewall rules</li></ul> |
| [Homelab: Secrets & Storage](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/07-vault/vault-setup.md) | ![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black) ![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white) | <ul><li>HashiCorp Vault as the centralized secrets manager for every VM/CT in the lab (scoped AppRoles, not the root token, for app and CI/CD deploys)</li><li>Self-hosted MinIO S3-compatible object storage</li></ul> |
| [CTF Writeups](https://github.com/tttaufiqqq/ctf-writeups) | ![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white) ![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![Ghidra](https://img.shields.io/badge/Ghidra-FF0000?style=flat-square&logoColor=white) ![Nmap](https://img.shields.io/badge/Nmap-004170?style=flat-square&logoColor=white) ![Gobuster](https://img.shields.io/badge/Gobuster-35495E?style=flat-square&logoColor=white) ![John](https://img.shields.io/badge/John_the_Ripper-black?style=flat-square&logoColor=white) | <ul><li>Notes and solutions from CTF challenges</li></ul> |

---

## CI/CD Pipelines

| Project | Tech Stack | Description |
|---|---|---|
| [BuzzyHive: CI/CD](https://github.com/tttaufiqqq/Kelulut-Hive-Harvest-Readiness-Prediction/blob/main/docs/ci-cd-pipeline/cicd-pipeline.md) | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![cPanel](https://img.shields.io/badge/Exabytes_cPanel-FF6C2C?style=flat-square&logo=cpanel&logoColor=white) | <ul><li>Cloud-hosted GitHub Actions pipeline with separate lint, deploy, and deploy-ml workflows</li><li>Deploys the Laravel app and retrains/ships the KNN classifier to cPanel hosting</li></ul> |
| [Animal Shelter Workshop: CI/CD](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/09-github-actions-runner/actions-runner-setup.md) | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) | <ul><li>Self-hosted GitHub Actions runner (LXC) on the tailnet, since CI and CD both need to reach private Tailscale-only DB hosts</li><li>Ansible converges all 6 fleet hosts on every CD run</li></ul> |
| [Animal Shelter Workshop: Deployment](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/11-vault-approle-app-integration/vault-approle-app-integration.md) | ![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black) ![Cloudflare](https://img.shields.io/badge/Cloudflare_Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white) | <ul><li>Deploy-time secrets pulled from a scoped Vault AppRole (not the root token) by Ansible</li><li>App goes live via a permanent Cloudflare Tunnel — no port-forwarding, no hardcoded `.env` credentials</li></ul> |

---

## DevOps Practice

A self-directed DevOps curriculum run against a real project (Animal Shelter Workshop) instead of tutorials: Terraform, Ansible, Docker, Kubernetes, observability, GitOps, and a multi-cloud stretch goal, each stage built, broken, and fixed for real.

| Project | Tech Stack | Description |
|---|---|---|
| [Homelab: Infrastructure as Code](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/02-terraform-state-import-and-module.md) | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white) | <ul><li>Proved the first real Terraform loop against production Proxmox infrastructure</li><li>Moved state onto a proper backend</li><li>Imported hand-provisioned containers</li><li>Replaced duplicated resource blocks with a for_each module</li></ul> |
| [Homelab: Configuration Management](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/03-ansible-roles-idempotency-molecule-vault-and-fleet-expansion.md) | ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) | <ul><li>Refactored a single giant Ansible task file into roles</li><li>Proved idempotency</li><li>Added Molecule testing</li><li>Expanded Vault-backed convergence across the fleet</li></ul> |
| [Homelab: CI/CD Hardening](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/04-ci-cd-per-connection-smoke-test-pre-deploy-backup-terraform-drift.md) | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) | <ul><li>Recovery path for failed DB deploys</li><li>Pre-deploy backup step</li><li>Terraform drift check surfaced on every run</li></ul> |
| [Homelab: Containers](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/05-docker-multi-stage-build-and-compose.md) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | <ul><li>Packaged the Laravel app (code, PHP runtime, built frontend) into a multi-stage Docker image</li><li>Compose stack for local testing — the first time it ran anywhere but a hand-configured VM</li></ul> |
| [Homelab: Kubernetes](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/06-k3s-single-node-deployment-and-vault-injector.md) | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black) | <ul><li>Deployed the containerized app onto a single-node k3s cluster with the Vault Agent Injector for secrets</li><li>Self-healing and rolling deploys instead of one container on one host</li></ul> |
| [Homelab: Observability](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/07-observability-prometheus-grafana-loki-alertmanager.md) | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) | <ul><li>Fleet-wide monitoring and log aggregation with Prometheus, Grafana, Loki, and Alertmanager</li><li>Replaces manual curl/kubectl/log-tailing checks with dashboards and alerts</li></ul> |
| [Homelab: GitOps](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/08-gitops-argocd-auto-sync-and-drift-revert.md) | ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) | <ul><li>ArgoCD watching the k3s cluster against Git, auto-syncing and reverting manual drift</li><li>Git became the enforced source of truth instead of a human running kubectl/helm/terraform by hand</li></ul> |
| [Homelab: Multi-Cloud (Azure)](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/blob/main/docs/19-devops-practice/09-azure-cloud-backup-sync.md) | ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | <ul><li>Offsite nightly database backup sync to Azure Blob Storage with a cost-guardrail budget</li><li>Azure Function reading Vault secrets through a Tailscale Funnel</li><li>Second Terraform provider (azurerm) proving the same IaC workflow against a different cloud</li></ul> |

---

## Technical Skills

**Languages**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Frameworks & Tools**

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Inertia.js](https://img.shields.io/badge/Inertia.js-9553E9?style=flat-square&logo=inertia&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Security & Testing**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-FF0000?style=flat-square&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-004170?style=flat-square&logoColor=white)
