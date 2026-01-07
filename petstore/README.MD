# CP Exam Vulnerable Lab

This project is an intentionally vulnerable lab created for educational and examination purposes.

---

## ⚠️ Disclaimer

This lab contains **intentional security vulnerabilities**.  
It must be used **ONLY in a local or isolated environment** for learning, examination, or CTF-style practice.

The author takes no responsibility for misuse.

---

## 🚀 How to Start the Lab

Start the environment
./start.sh

Stop the environment
./stop.sh

Full reset (recommended if something breaks)
./reset.sh


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

