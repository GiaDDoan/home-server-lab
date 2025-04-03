# 🏠 Home Server Lab – Fedora, Docker, VPN & Private Cloud

This is an **ongoing personal project** where I’m building a self-hosted home server on **Fedora 41** to deploy and secure various services using Docker, reverse proxies, and VPNs. The goal is to simulate real-world IT infrastructure, improve my skills in system and network administration, and host reliable private cloud services.

This lab continues to evolve as I test new tools, implement better security practices, and add new services over time.

---

## 📌 Table of Contents

- [Goals](#goals)
- [Architecture Overview](#architecture-overview)
- [Core Technologies](#core-technologies)
- [Key Features](#key-features)
- [Service Breakdown](#service-breakdown)
- [Security & Access](#security--access)
- [Future Plans](#future-plans)
- [Screenshots](#screenshots-optional)

---

## 🎯 Goals

- Host personal cloud services securely from home.
- Learn and apply self-hosting, networking, and VPN concepts.
- Practice containerization and infrastructure management with Docker.
- Explore private cloud alternatives to mainstream SaaS tools.
- Harden the setup using DNS, firewall, and SSL best practices.

---

## 🌐 Architecture Overview

![Image](https://github.com/user-attachments/assets/ce1ee4dd-c212-4fbb-9700-244b2b5e26f9)

---

## 🧰 Core Technologies

| Category           | Tools / Services                          |
|--------------------|-------------------------------------------|
| OS                 | Fedora 41                                 |
| Virtualization     | Docker + Portainer                        |
| Reverse Proxy      | Nginx Proxy Manager                       |
| Cloud Storage      | Nextcloud                                 |
| Password Manager   | Bitwarden                                 |
| Network Filtering  | Pi-hole                                   |
| Remote Access      | VPN                                       |
| DNS & Security     | Cloudflare (DNS, ACLs, SSL)              |

---

## 🚀 Key Features

- **Secure Remote Access** with a private VPN
- **Containerized Deployment** using Docker + Portainer
- **Dynamic DNS + SSL Management** with Nginx Proxy Manager
- **Self-Hosted Cloud** via Nextcloud (files, calendar, contacts)
- **Password Manager** with Bitwarden
- **Ad/Tracker Blocking** via Pi-hole
- **Public Access Control** with Cloudflare DNS & firewall
- **Expandable**: easily add new services to the stack

---

## 📦 Service Breakdown

### 🔐 VPN
- Private VPN for secure remote access to the server and services
- Allows access without exposing ports to the open internet

### 🐳 Docker & Portainer
- Easy management of containerized services
- Isolation, portability, and scalability for lab environments

### 🌐 Nginx Proxy Manager
- Reverse proxy for internal services
- Automated Let's Encrypt SSL
- Custom subdomain routing and access rules

### ☁️ Nextcloud
- Private cloud solution for file storage and synchronization
- Web and mobile access
- Shared calendars, contacts, and apps

### 🔐 Bitwarden
- Self-hosted password manager for secure credential storage
- Web access and integration with browser/mobile apps

### 🛑 Pi-hole
- DNS-based ad and tracker blocker for the home network
- Enhances privacy and network performance

### ☁️ Cloudflare
- Public DNS management
- Firewall rules and access control lists (ACLs)
- Enhanced SSL/TLS handling and caching

---

## 🛡️ Security & Access

- **VPN Tunnel**: All remote access is routed through a secure VPN
- **Reverse Proxy Rules**: Nginx enforces domain and SSL policies
- **Cloudflare ACLs**: Limits access to specific IPs / regions
- **Automatic SSL**: via Let's Encrypt for all services
- **No direct port exposure**: services only accessible via VPN or proxy

---

## 🧠 Future Plans

- Integrate uptime monitoring (e.g. Uptime Kuma)
- Deploy a personal dashboard for service overview
- Add Home Assistant for smart home integration
- Automate backups to cloud storage
- Set up logging/monitoring via Grafana + Prometheus

---

## 🖼️ Screenshots

> _Coming soon — stay tuned for dashboards, Nextcloud interface, and network overview._

