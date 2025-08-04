# 🚀 Dockerized WordPress with NGINX Reverse Proxy

A simple and production-ready Docker setup for running **WordPress**, **MySQL**, **phpMyAdmin**, and an **NGINX reverse proxy with SSL**.

> 🛠️ Ideal for local development, staging environments, or self-hosted WordPress deployments.

---

## 🧱 Tech Stack

- **WordPress** (latest with PHP 8.2)
- **MySQL 8**
- **phpMyAdmin**
- **NGINX** reverse proxy with SSL
- **Docker Compose**

---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/JinalSolanki52/Wordpress-Docker.git
cd wordpress-docker
```

### 2. SetUp Environment Variables

```bash
nano .env
```

### 3. Start the Containers

```bash
docker-compose up -d
```

### 🌐 Access

| Service    | URL                                                                          |
| ---------- | ---------------------------------------------------------------------------- |
| WordPress  | [https://wordpress.example.com](https://wordpress.example.com)                         |
| phpMyAdmin | [https://wordpress.example.com/phpmyadmin/](https://wordpress.example.com/phpmyadmin/) |

⚠️ Use https:// to avoid SSL errors.
