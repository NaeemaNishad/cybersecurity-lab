# 🐧 Linux Cheat Sheet

A quick reference guide for essential Linux commands and basic cybersecurity tools used in Kali Linux.

---

## 📁 File System Navigation

- `pwd` → Show current working directory  
- `ls` → List files and directories  
- `cd /home` → Change directory  

---

## 🔐 File & Directory Permissions

- `mkdir lab_test` → Create a directory  
- `cd lab_test` → Enter directory  
- `touch file.txt` → Create a file  

- `chmod 777 file.txt` → Change file permissions  
- `chown kali:kali file.txt` → Change file ownership  

- `ls -l` → View file permissions  

---

## 📦 Package Management

- `sudo apt update` → Update package list  
- `sudo apt install net-tools` → Install package  
- `dpkg -l | grep net-tools` → Verify installed package  

---

## 🌐 Networking Commands

- `ifconfig` → Display IP address  
- `ping google.com` → Check network connectivity  
- `netstat -tulnp` → Show open ports and services  
- `traceroute google.com` → Trace route to destination  

---

## 🔐 Cryptography Commands

- `echo "Hello Cybersecurity" > file.txt` → Create a file  

- `openssl enc -aes-256-cbc -salt -in file.txt -out encrypted.txt`  
  → Encrypt file using AES-256  

- `openssl enc -aes-256-cbc -d -in encrypted.txt -out decrypted.txt`  
  → Decrypt file  

- `cat decrypted.txt` → View decrypted content  

---

## 🛠️ Tool Familiarization Commands

### 🔎 Nmap (Network Scanning)

- `nmap <ip>` → Basic scan  
- `nmap -sV -sC <ip>` → Service version detection + default scripts  
- `nmap -A <ip>` → Aggressive scan (OS detection, version, scripts)  

---

### 💣 Metasploit Framework

- `msfconsole` → Start Metasploit Framework  

#### 🔍 Search Exploits
- `search vsftpd`  
- `search samba`  
- `search unreal`  
- `search tomcat`  

#### ⚙️ Using an Exploit
- `use exploit/unix/ftp/vsftpd_234_backdoor`  
- `show options`  
- `set RHOSTS <target_ip>` → Set target IP  
- `set RPORT 21` → Set target port  
- `run` → Execute exploit  

---

## ⚠️ Note
- Replace `<ip>` or `<target_ip>` with the actual IP address of the target machine (e.g., Metasploitable).  
