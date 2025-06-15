# 🚀 Moore App

> “The Future of AI-Powered Logistics”  
> A next-gen logistics platform powered by smart routing, real-time data, and adaptive automation.

## 📌 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Deployment Steps](#deployment-steps)
- [Dynamic Content](#dynamic-content)
- [Security](#security)
- [Screenshots](#screenshots)
- [Public Access](#public-access)

---

## 🔍 Overview

This project is a cloud-hosted prototype designed to demonstrate full-stack engineering and cloud deployment skills. It includes:

- Server provisioning on AWS EC2
- Nginx reverse proxy
- Tailwind-enhanced frontend

---

## ⚙️ Tech Stack

- **Cloud**: AWS EC2 (Ubuntu 22.04)
- **Web Server**: Nginx (reverse proxy)
- **Frontend**: HTML, Tailwind CSS

---

## ✨ Features

- Dynamic landing page with personalized bio
- Tailwind CSS animations
- Professionally structured and deployed

---

## 🚀 Deployment Steps

### 1. Provision the Server

- Cloud: [AWS EC2](https://aws.amazon.com/ec2/)
- Image: Ubuntu 22.04 LTS
- Instance Type: `t2.micro` (free-tier eligible)
- Open ports: **22**, **80**

### 2. Connect to the Server

Use SSH to connect to your instance:

### 3. Install Nginx
sudo apt update
sudo apt install nginx -y

### 4. Configure Firewall
sudo ufw allow 'Nginx HTTP'
sudo ufw enable

### 5. Deploy web files
mkdir landing-page
cd landing-page

sudo chmod 644 /home/ubuntu/landing-page/index.html
sudo chmod 755 /home/ubuntu/landing-page
sudo chmod o+x /home/ubuntu
