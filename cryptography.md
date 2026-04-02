# 🔐 Cryptography Notes

A brief overview of fundamental cryptography concepts and practical implementation using OpenSSL.

---

## 🔑 Encryption Types

### 🔹 Symmetric Encryption
Symmetric encryption uses a **single key** for both encryption and decryption.

- Fast and efficient  
- Requires secure key sharing  

**Example:** AES (Advanced Encryption Standard)

---

### 🔹 Asymmetric Encryption
Asymmetric encryption uses **two keys**:

- **Public Key** → Used for encryption  
- **Private Key** → Used for decryption  

- More secure than symmetric encryption  
- Slower in performance  

**Example:** RSA (Rivest-Shamir-Adleman)

---

## 🧮 Hashing

Hashing is the process of converting data into a **fixed-length hash value**.

- One-way process (cannot be reversed)  
- Used for data integrity and password storage  

### Common Algorithms:
- **MD5** → Produces a 128-bit hash (less secure)  
- **SHA-256** → Produces a 256-bit hash (more secure)  

---

## 📜 Digital Certificates & SSL/TLS

- **Digital Certificates** verify the identity of websites and organizations  
- **SSL (Secure Sockets Layer)** and **TLS (Transport Layer Security)** encrypt data during transmission  

👉 Used in **HTTPS** to secure communication between client and server  

---

## 🧪 Practical: OpenSSL Commands

### 📄 Create a File
```bash
echo "Hello Cybersecurity" > file.txt
