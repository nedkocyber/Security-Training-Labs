# MegaBank CTF

This project is an intentionally vulnerable banking system created for educational purposes, exams, and CTF competitions.

## ⚠️ Disclaimer

This lab contains intentional security vulnerabilities.  
It must be used **ONLY** in a local or isolated environment for learning, testing, or CTF practice.

## 🎯 Goal

Find as many vulnerabilities as possible and try to achieve **Remote Code Execution (RCE)**.  
There are **10+ vulnerabilities** waiting to be discovered.

## 🧩 Lab Components

- Vulnerable PHP web application with three distinct user roles
- MySQL database
- phpMyAdmin (for database management)
- FTP server
- All services containerized with Docker & Docker Compose

## 🚀 How to Start the Lab

### !!! Install the CTF !!!

```bash
wget https://raw.githubusercontent.com/nedkocyber/Security-Training-Labs/main/petstore/bank_ctf_backup_20260414_095239.tar.gz
```
Or if not working just download it as zip.

After that unzip the file with

```
tar -xzvf bank_ctf_backup_20260414_095239.tar.gz
```
Next navigate to the direcotry BankCTF and start the start.sh script

## 🐳 Docker Requirements

### 1️⃣ Install Docker
```
sudo apt update

sudo apt install docker.io -y

sudo systemctl enable docker

sudo systemctl start docker
```
### 2️⃣ Install Docker Compose
```
sudo apt install docker-compose -y
```
### 3️⃣ Verify Installation
```
docker --version
docker compose version
```

