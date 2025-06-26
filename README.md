# 🔓 BurpSuite-Pro-free

A streamlined setup script to get **Burp Suite Professional (v2025.5.5)** running for penetration testing and web application security assessments. This repository automates the download and environment setup so you can focus on what matters — **hacking**.

---

## ⚙️ Features

- ✅ One-liner install and setup
- ☕ Compatible with OpenJDK 21, 22, and 23
- 🚀 Fast download via `axel` and `curl`
- 🧩 Supports Burp Pro JAR loading via `loader.jar`
- 🔐 Clean installation using `apt`

---

## 📥 Quick Start

Clone and run:

```bash
git clone https://github.com/SIAM-T/burpsuite.git
cd burpsuite
sudo apt update -y
sudo apt upgrade -y
sudo apt install axel openjdk-21-jre openjdk-22-jre openjdk-23-jre -y
curl -L "https://portswigger.net/burp/releases/startdownload?product=pro&version=2025.5.5&type=jar" -o burpsuite_pro_v2025.5.5.jar
java -jar loader.jar
