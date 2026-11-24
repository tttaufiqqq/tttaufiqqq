## Cloud Projects (Azure)

| Project | Tech Stack | Description |
|---|---|---|
| [BuzzyHive on Azure: Container Apps + Terraform](https://github.com/tttaufiqqq/buzzyhive-azure-infra) | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Azure](https://img.shields.io/badge/Azure_Container_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL_Flexible_Server-4479A1?style=flat-square&logo=mysql&logoColor=white) ![IoT Hub](https://img.shields.io/badge/Azure_IoT_Hub-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) | <ul><li>Runs BuzzyHive 2.0 (a Laravel + React app with a Flask KNN readiness model) on Azure Container Apps, with Terraform split into three roots: remote state, governance and identity, and a destroyable lab</li><li>Docker images for Laravel (FrankenPHP on Alpine) and Flask in Azure Container Registry, MySQL Flexible Server, Key Vault secrets read through a managed identity, IoT Hub with a device simulator, Azure Policy, a budget and alerts</li><li>Deployed and smoke-tested end to end; a k6 load test at 10 requests/s exposed MySQL deadlocks and liveness-probe restarts, investigated with Log Analytics queries and Container Apps metrics</li><li>33 troubleshooting entries, numbered evidence screenshots (blurred before publishing) and a decisions log</li></ul> |
| [Azure Virtual WAN: Private Link + DNS](https://github.com/tttaufiqqq/azure-private-link-dns) | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Azure](https://img.shields.io/badge/Azure_Virtual_WAN-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure Firewall](https://img.shields.io/badge/Azure_Firewall-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![DNS Private Resolver](https://img.shields.io/badge/DNS_Private_Resolver-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | <ul><li>Reproduced and fixed a Private Link DNS failure in a secured Virtual WAN hub: a VM behind the firewall resolved a storage account to its public IP until a DNS Private Resolver hub extension made it resolve the private endpoint</li><li>Modular Terraform with NSG/ASG hardening, Azure Bastion, and an optional second region sharing one private DNS zone</li><li>Firewall DNS and rule logs queried with KQL in Log Analytics; evidence, diagrams and troubleshooting log included</li></ul> |
| [Cache-Aside Architecture on Azure](https://github.com/tttaufiqqq/azure-cache-aside-infra-architecture) | ![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure](https://img.shields.io/badge/Azure_App_Service-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Redis](https://img.shields.io/badge/Azure_Managed_Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | <ul><li>Bicep infrastructure for the Azure cache-aside pattern: App Service, Azure Managed Redis and PostgreSQL Flexible Server</li><li>Data traffic on private endpoints and private DNS zones, with passwordless access through a user-assigned managed identity and Microsoft Entra ID</li><li>Log Analytics and Application Insights monitoring; fixed a Redis capacity error by redeploying to another region</li></ul> |
| [Azure Administration Lab (AZ-104 Aligned)](https://github.com/tttaufiqqq/azure-az104-lab) | ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Azure Backup](https://img.shields.io/badge/Azure_Backup-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | <ul><li>Connected Azure environment across six project folders: Entra ID users and groups, RBAC, private networking and storage, VM security, monitoring and backup</li><li>Conditional Access with MFA, Privileged Identity Management with approval-based activation, and a tested Azure Backup restore</li><li>Each project documented with numbered screenshots, KQL queries and troubleshooting notes</li></ul> |

---

## System Projects

| Project | Tech Stack | Description |
|---|---|---|
| [BuzzyHive 2.0](https://github.com/tttaufiqqq/Kelulut-Hive-Harvest-Readiness-Prediction) | ![Laravel](https://img.shields.io/badge/Laravel_13-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) ![Inertia.js](https://img.shields.io/badge/Inertia.js-9553E9?style=flat-square&logo=inertia&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![cPanel](https://img.shields.io/badge/Exabytes_cPanel-FF6C2C?style=flat-square&logo=cpanel&logoColor=white) | <ul><li>Final Year Project: IoT + ML system for kelulut (stingless bee) harvest readiness monitoring</li><li>ESP32 sensors push live data, KNN classifier predicts readiness, Telegram alerts beekeepers</li><li>Deployed via a GitHub Actions CI/CD pipeline (lint, deploy, deploy-ml stages)</li><li>Live at buzzyhive.urban-alert.com</li></ul> |
| [Animal Shelter Workshop](https://github.com/tttaufiqqq/Animal-Shelter-Workshop) | ![Laravel](https://img.shields.io/badge/Laravel_11-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![Livewire](https://img.shields.io/badge/Livewire-4E56A6?style=flat-square&logo=livewire&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) | <ul><li>Animal rescue and adoption platform with 5 databases across 3 engines (PostgreSQL, MySQL, MariaDB) on a Tailscale VPN mesh</li><li>Cross-database relationships enforced at the application layer</li><li>BITU3923 Workshop II</li></ul> |


## DevOps Practice

| Project | Tech Stack | Description |
|---|---|---|
| [Homelab: End-to-End DevOps](https://github.com/tttaufiqqq/proxmox-homelab-taufiq/tree/main/docs/19-devops-practice) | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white) | <ul><li>Self-directed DevOps pipeline run against a real 5-database Laravel app ([Animal Shelter Workshop](https://github.com/tttaufiqqq/Animal-Shelter-Workshop)) on a Proxmox homelab, built, broken and fixed for real</li><li>Infrastructure as code with Terraform and Ansible (roles, Molecule tests, Vault-backed secrets)</li><li>Dockerized app on a 2-node k3s cluster with GitOps via ArgoCD that auto-reverts manual drift</li><li>Hardened CI/CD with pre-deploy backups and drift checks, plus Prometheus, Grafana, Loki and Alertmanager for fleet-wide monitoring</li></ul> |

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
