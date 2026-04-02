# Linux Cheat Sheet

## File System Navigation
pwd - show current working directory  
ls - list files and directories  
cd /home - change directory  

## File & Directory Permissions
mkdir lab_test - create directory  
cd lab_test - enter directory  
touch file.txt - create file  

chmod 777 file.txt - change file permissions  
chown kali:kali file.txt - change file ownership  

ls -l - view permissions  

## Package Management
sudo apt update - update package list  
sudo apt install net-tools - install package  
dpkg -l | grep net-tools - check installed package  

## Networking Commands
ifconfig - show IP address  
ping google.com - check connectivity  
netstat -tulnp - show open ports  
traceroute google.com - trace route  

## Cryptography Commands
echo "Hello Cybersecurity" > file.txt - create file  

openssl enc -aes-256-cbc -salt -in file.txt -out encrypted.txt - encrypt file  

openssl enc -aes-256-cbc -d -in encrypted.txt -out decrypted.txt - decrypt file  

cat decrypted.txt - view decrypted content  
