# 🧭 Rookie Recon

**Welcome to Level 2: Rookie Recon!**  
This phase focuses on *reconnaissance* — the art of gathering information about your target using open-source tools and passive techniques before attempting any active engagement.

---

## 🌐 1. OSINT Basics (Open Source Intelligence)
- What is OSINT?
- Why reconnaissance matters in ethical hacking
- Legal & ethical considerations
- Types of intel: people, companies, websites, infrastructure
- Real-world examples

---

## 🔎 2. Domain & Network Reconnaissance
### WHOIS Lookups
- Understand domain registration info
- Tools:
  - `whois`
  - [Whoxy](https://www.whoxy.com/)
  - [ICANN Lookup](https://lookup.icann.org/)

### DNS Enumeration
- Discover subdomains, mail servers, and name servers
- Tools:
  - `nslookup`
  - `dig`
  - `host`
  - `dnsenum`
  - `Fierce`

### IP Lookup
- Reverse DNS
- Geolocation
- ASN info

---

## 🗺️ 3. Host & Network Scanning
### Nmap Basics
- Port scanning: TCP vs UDP
- Service detection (`-sV`)
- OS detection (`-O`)
- Stealth scanning (`-sS`)
- Intro to NSE (Nmap Scripting Engine)

### Banner Grabbing
- Reveal service info using:
  - `netcat`
  - `telnet`
  - `curl`

---

## ⚙️ 4. Recon Tools Overview
- 🛠️ [`theHarvester`](https://github.com/laramies/theHarvester)
- 🕵️‍♂️ [`Recon-ng`](https://github.com/lanmaster53/recon-ng)
- 🧠 [`SpiderFoot`](https://github.com/smicallef/spiderfoot)
- 🌐 [`Shodan`](https://www.shodan.io/)
- 🔎 [`Censys`](https://censys.io/)
- 🌍 [`Amass`](https://github.com/owasp-amass/amass)
- 🧬 [`Maltego`](https://www.maltego.com/)

---

## 👥 5. People & Organization Footprinting
- Email & username discovery
- Useful tools:
  - [Hunter.io](https://hunter.io)
  - [HaveIBeenPwned](https://haveibeenpwned.com)
  - [Pipl](https://pipl.com) *(some features paid)*
- LinkedIn scraping & employee discovery
- Social media recon
- Google Dorking for specific info
- Building a digital footprint

---

## ⚖️ 6. Manual vs Automated Recon
- Why automation isn't everything
- How human intuition improves results
- When to go manual and verify

---

## 🧪 7. Practical Labs
- 🎓 [TryHackMe – OSINT Basics](https://tryhackme.com/room/osint)
- 🎓 [TryHackMe – Intro to Recon](https://tryhackme.com/room/introtorecon)
- 🧩 Hack The Box recon-focused machines
- 🕵️‍♀️ CTFs (e.g. OSINT Dojo, Trace Labs)

---
