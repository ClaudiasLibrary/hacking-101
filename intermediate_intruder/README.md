# Intermediate Intruder

<img src="https://cdn-cf.ginx.tv/imgcdn/g3RwjOlZ-iZ8J6tuI4USf55jmOeqhCLMpPr-aFcZa-w/rs:fill:2400:0:1/g:ce/aHR0cHM6Ly93d3cuZ2lueC50di91cGxvYWRzL05ld0ZvbGRlci9DeWJlcnB1bmtfMjA3N19OZXRydW5uZXJfYnVpbGQvY3liZXJwdW5rXzIwNzdfbmV0cnVubmVyX2NvdmVyLmpwZw" alt="cyberpunk" width="550" height="300">

**Welcome to Level 3: Intermediate Intruder**  
In this phase, we move from passive recon into active probing, vulnerability identification, and even basic exploitation. You now know what your target looks like — it's time to see how it holds up.

---

## 🧪 1. Active Scanning Techniques

### Nmap Advanced Scanning
- Aggressive scan mode (`-A`)
- NSE (Nmap Scripting Engine) scripts for:
  - Vuln detection
  - Default creds
  - CVE discovery
- Output parsing (XML/grepable formats)
- Timing and evasion techniques (`-T`, `--data-length`, `--source-port`)

### Other Tools:
- [`RustScan`](https://github.com/RustScan/RustScan) – fast port scanner
- [`Masscan`](https://github.com/robertdavidgraham/masscan) – Internet-wide scanning

---

## 🧱 [2. Service Enumeration](https://claudiaslibrary.notion.site/Enumeration-13219f75683280b1ad52fd9bfcb7367f)

### Common Services
- **SMB**: `enum4linux`, `smbclient`, `smbmap`
- **FTP**: Anonymous login, `ftp`, `nmap` scripts
- **SSH**: Version fingerprinting, brute force warnings
- **Web**: HTTP headers, robots.txt, `whatweb`, `nikto`

### Web Tech Fingerprinting
- `whatweb`, `wappalyzer`, `builtwith`, `nmap -sV`

---

## 🔍 [3. Vulnerability Scanning](https://claudiaslibrary.notion.site/Vulnerability-Scans-13219f7568328026a09bfc4a099fddd7)

### Tools to Introduce
- [`Nessus`](https://www.tenable.com/products/nessus)
- [`OpenVAS`](https://www.greenbone.net/)
- [`Nuclei`](https://github.com/projectdiscovery/nuclei) – fast CVE scanning
- [`Nikto`](https://github.com/sullo/nikto)
- [`searchsploit`](https://github.com/offensive-security/exploitdb)

### CVE Hunting
- Understanding CVSS scores
- CVE search tools: `searchsploit`, `cve.sh`, Google-fu

---

## 🧨 4. Basic Exploitation

### Metasploit Framework (MSF)
- Setting up `msfconsole`
- Using `search`, `info`, `use`, `set`, `exploit`
- Example: Exploiting vulnerable FTP server

### Manual Exploitation Intro
- Reverse shell basics
- Exploiting web vulnerabilities:
  - SQLi basics (`sqlmap`)
  - Command injection
  - File inclusion (LFI/RFI)
  - XSS intro (for payload discovery, not just alert boxes)

---

## 📡 5. Brute Forcing & Credential Attacks

### Tools
- `hydra`
- `medusa`
- `john` / `hashcat` (intro only)
- Wordlists: `rockyou.txt`, SecLists

### Targets
- SSH
- FTP
- Web login forms (using Burp Suite or Hydra with POST)

> ⚠️ Ethical Reminder: Only perform brute forcing on **authorized** systems with **explicit permission**!

---

## 🕸️ [6. Web App Security – Basics](https://claudiaslibrary.notion.site/Web-Applications-Vulnerabilities-12b19f756832801f9e2dd32a86bd628b)

### Introduce OWASP Top 10
- A01: Broken Access Control
- A03: Injection (SQLi, XSS)
- A05: Security Misconfiguration
- A07: Identification & Authentication Failures

### Tools to Practice:
- `Burp Suite` (Community Edition)
- `OWASP ZAP`
- `sqlmap`

---

## 🧪 7. Labs & Practice Platforms

- [TryHackMe – Metasploit](https://tryhackme.com/room/metasploit)
- [TryHackMe – Vulnversity](https://tryhackme.com/room/vulnversity)
- [Hack The Box – Easy Machines](https://www.hackthebox.com/)
- [DVWA](http://www.dvwa.co.uk/) – Damn Vulnerable Web Application
- [bWAPP](http://www.itsecgames.com/)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)

---

## 📚 8. Resources & Further Learning

- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [HackTricks](https://book.hacktricks.xyz/)
- [Exploit-DB](https://www.exploit-db.com/)
- [Red Team Notes](https://github.com/antonioCoco/Red-Teaming-Notes)

---
