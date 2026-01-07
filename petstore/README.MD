# CP Exam Vulnerable Lab

This project is an intentionally vulnerable lab created for educational and examination purposes.

---

## ⚠️ Disclaimer

This lab contains **intentional security vulnerabilities**.  
It must be used **ONLY in a local or isolated environment** for learning, examination, or CTF-style practice.

The author takes no responsibility for misuse.

---

## 🎯 Goal
In this lab there are 3 flags in total - every next flag gets more complicated to find.
The contents of each flag follow this format: Good job finding the flag! (or similar congratulatory message) - so when you find it, you will know!

---

## 🚀 How to Start the Lab

Start the environment

./start.sh

Stop the environment

./stop.sh

Full reset (recommended if something breaks)

./reset.sh

---

## 🌐 Access Information
Once the lab is running, you can access it through:

Localhost: http://127.0.0.1 or http://localhost

Network Interface: Access via your machine's IP address on eth0 interface

```bash
# Find your IP address on eth0
ip addr show eth0 | grep inet
```
## 🧩 Lab Components

- Vulnerable PHP Web Application
- MySQL Database
- FTP Server (vsftpd)
- Docker & Docker Compose environment

All services are containerized and automatically configured.

---

## 🐳 Docker Requirements

### 1️⃣ Install Docker

sudo apt update

sudo apt install docker.io -y

sudo systemctl enable docker

sudo systemctl start docker

### 2️⃣ Install Docker Compose

sudo apt install docker-compose -y
### 3️⃣ Verify Installation

docker --version
docker compose version

