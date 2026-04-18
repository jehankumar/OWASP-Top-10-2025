# 🔐 OWASP Top 10 2025 

This repository documents my learning and hands-on practice of the **OWASP Top 10 (2025)**.  
It covers all major web application security risks with simple explanations and practical insights.

---

## 📚 OWASP Top 10 (2025)

### 🔓 A01: Broken Access Control
- Failure to enforce proper user permissions
- Example: Changing `?id=1` to `?id=2` (IDOR)
- Impact:
  - Unauthorized data access
  - Privilege escalation

---

### ⚙️ A02: Security Misconfiguration
- Improper system or server configuration
- Examples:
  - Default credentials
  - Open admin panels
  - Debug mode enabled
- Impact:
  - Full system exposure

---

### 🔗 A03: Software Supply Chain Failures
- Using vulnerable or tampered dependencies
- Examples:
  - Outdated libraries
  - Compromised packages
- Impact:
  - Backdoor access
  - Large-scale attacks

---

### 🔐 A04: Cryptographic Failures
- Weak or missing encryption
- Examples:
  - Plain text passwords
  - Weak hashing (MD5, SHA1)
  - HTTP instead of HTTPS
- Impact:
  - Data breaches
  - Sensitive data exposure

---

### 💉 A05: Injection
- Unsanitized user input executed as code
- Types:
  - SQL Injection
  - Command Injection
  - Template Injection
- Impact:
  - Data theft
  - Remote code execution

---

### 🧩 A06: Insecure Design
- Security not considered during design phase
- Examples:
  - No rate limiting
  - Poor authentication flow
- Impact:
  - Hard-to-fix fundamental flaws

---

### 🔑 A07: Authentication Failures
- Weak login or session handling
- Examples:
  - No brute-force protection
  - Logic flaws (case-sensitive issues)
- Impact:
  - Account takeover
  - Admin access

---

### 📦 A08: Software & Data Integrity Failures
- Trusting unverified code or data
- Examples:
  - Insecure deserialization
  - No integrity checks
- Impact:
  - Remote code execution
  - Supply chain attacks

---

### 📜 A09: Logging & Monitoring Failures
- Missing or weak logging systems
- Examples:
  - No login logs
  - No alerts for suspicious activity
- Impact:
  - Attacks go undetected

---

### 🌐 A10: Server-Side Request Forgery (SSRF)
- Server makes requests to unintended locations
- Examples:
  - Accessing internal services
  - Hitting cloud metadata endpoints
- Impact:
  - Internal network exposure
  - Data leakage

---

## 🎯 Purpose of This Repo

- 📖 Document my cybersecurity learning journey  
- 🧠 Understand OWASP Top 10 in simple terms  
- 🛠️ Practice real-world vulnerabilities  

---

## ⚠️ Disclaimer

This content is for **educational purposes only**.  
Do not use these techniques on systems without proper authorization.

---

## 🤝 Contributing

Contributions are welcome! Feel free to improve or expand the content.
