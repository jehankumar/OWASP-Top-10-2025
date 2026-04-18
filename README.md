# 🔐 OWASP Top 10 2025

This repository contains my notes and practical learning from the OWASP Top 10 (2025).  
The goal is to understand real-world web security vulnerabilities in a simple and hands-on way.

---

## 📚 Topics Covered

### IAAA Failures
- A01: Broken Access Control  
- A07: Authentication Failures  
- A09: Logging & Monitoring Failures  

### Application Design Flaws
- A02: Security Misconfigurations  
- A03: Software Supply Chain Failures  
- A04: Cryptographic Failures  
- A06: Insecure Design  

### Insecure Data Handling
- A04: Cryptographic Failures  
- A05: Injection  
- A08: Software or Data Integrity Failures  

---

## 🧠 What is IAAA?

IAAA stands for:

- **Identity** – Who the user is  
- **Authentication** – Verifying the user  
- **Authorization** – What they can access  
- **Accountability** – Tracking user actions  

Each step depends on the previous one. If one fails, security breaks.

---

## 🔍 Key Learnings

### 🔓 A01: Broken Access Control
- Improper permission checks
- Example: Changing `accountID` in URL (IDOR)
- Can lead to:
  - Data leaks
  - Unauthorized access
  - Privilege escalation

---

### 🔑 A07: Authentication Failures
- Weak login or logic flaws
- Example:
  - Registering `aDmiN` instead of `admin`
- Can lead to:
  - Account takeover
  - Admin access

---

### 📜 A09: Logging & Monitoring Failures
- Missing or weak logs
- Makes it hard to detect attacks
- Important for:
  - Incident response
  - Tracking attackers

---

### 🔐 A04: Cryptographic Failures
- Weak or missing encryption
- Common issues:
  - Plain text passwords
  - Weak hashing
  - Using HTTP instead of HTTPS
- Leads to data exposure

---

### 💉 A05: Injection
- Unsafe handling of user input
- Examples:
  - SQL Injection
  - Command Injection
- Can lead to:
  - Data theft
  - System compromise

---

### ⚠️ A08: Software/Data Integrity Failures
- Trusting unverified code or updates
- Examples:
  - Tampered libraries
  - Insecure deserialization
- Leads to supply chain attacks

---

## 🧪 Hands-on Practice

Each topic includes practical tasks to:
- Understand vulnerabilities
- Exploit them safely
- Learn real-world attack scenarios

---

## 🎯 Purpose

- Document my cybersecurity learning
- Simplify OWASP concepts
- Focus on practical understanding

---

## ⚠️ Disclaimer

This is for educational purposes only.  
Do not test these techniques on systems without permission.

---

## 🤝 Contributing

Feel free to contribute or improve explanations.
