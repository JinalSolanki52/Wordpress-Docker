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


### 📸 Screenshots 
WordPress
<img width="783" height="640" alt="Screen Shot 2025-08-04 at 12 14 53 PM" src="https://github.com/user-attachments/assets/488567e0-1b00-419d-8c81-22c94c9e47a0" />

phpmydmin
<img width="778" height="454" alt="Screen Shot 2025-08-04 at 12 17 04 PM" src="https://github.com/user-attachments/assets/98b29053-e672-4b9b-97b2-715228c5bdf6" />


