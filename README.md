# 🛡️ Honeypot Security Project

## 📌 Overview
This project involves setting up a **honeypot** to detect unauthorized access attempts and analyze attack patterns. The honeypot was deployed on a **Kali Linux VM** and logged real-world attack data.  

## 🚀 Features
- Captures unauthorized access attempts  
- Logs attacker's **IP, payloads, and timestamps**  
- Uses **Dionaea / Cowrie** for SSH/Telnet monitoring  
- Generates reports for **threat analysis**  

## 🔧 Setup & Installation
### **1️⃣ Install Dependencies**
Run the following commands to install and configure the honeypot:  
```bash
sudo apt update && sudo apt install cowrie -y
cd /opt/
git clone https://github.com/micheloosterhof/cowrie.git
cd cowrie
cp cowrie.cfg.dist cowrie.cfg

