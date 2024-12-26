# Script Kiddie Start

<img src="https://preview.redd.it/jbcj0uqbihg41.jpg?auto=webp&s=b64638891773bc197f6e38c6b29c157b8f162e20" alt="hacker meme" width="500" height="300">

This document provides a comprehensive list of topics and skills to learn for beginners in cybersecurity, categorized under the **Script Kiddie Start** level. The focus is on building foundational knowledge and skills to set the stage for advanced levels.

## 1. Basic Computer Skills

Understanding basic computer skills is essential for navigating and troubleshooting systems effectively. These skills form the groundwork for more complex cybersecurity concepts.

### Topics to Learn:

1. **File Management:**
   - Creating, renaming, and deleting files and folders across operating systems like Windows and Linux.
   - Understanding file extensions and types (e.g., .txt, .jpg, .exe) and their purposes.
   - Copying and moving files between directories, including using drag-and-drop or command-line tools.
   - Organizing files into structured directories to maintain clarity and accessibility.

2. **Operating Systems Basics:**
   - Understanding the differences between Windows, Linux, and macOS, including their file systems and user interfaces.
   - Navigating essential components like the desktop, taskbar, and system menus.
   - Installing, updating, and uninstalling software, with attention to safe download practices.
   - Recognizing system information, such as version numbers and specifications, for troubleshooting.

3. **Using the Command Line:**
   - Executing basic commands like `cd` (change directory), `ls` (list files), and `mkdir` (create directory).
   - Understanding file paths and the difference between relative and absolute paths.
   - Editing files using command-line editors like `nano` or `vim`, with examples such as creating or modifying configuration files.
   - Using command-line tools to check system status (e.g., `df` for disk usage, `top` for processes).

4. **Internet Browsing Skills:**
   - Conducting advanced searches using operators like `site:`, `filetype:`, and quotation marks for precise results.
   - Understanding URLs, hyperlinks, and bookmarks, including identifying suspicious links.
   - Clearing browser cache, cookies, and browsing history to enhance privacy and performance.
   - Configuring browser extensions for security, such as ad blockers and HTTPS enforcement.

5. **Basic Troubleshooting:**
   - Identifying and interpreting common error messages, such as "Access Denied" or "File Not Found."
   - Restarting applications or systems to resolve simple technical issues.
   - Checking and updating software, drivers, and firmware to maintain compatibility and security.
   - Using built-in diagnostic tools (e.g., Windows Troubleshooter, Linux logs) for deeper troubleshooting.

6. **Keyboard Shortcuts:**
   - Learning common shortcuts like `Ctrl+C` (copy), `Ctrl+V` (paste), and `Ctrl+Z` (undo) to increase efficiency.
   - Navigating applications with `Alt+Tab` (Windows) or `Cmd+Tab` (macOS).
   - Mastering terminal shortcuts like `Ctrl+A` (go to beginning of line) and `Ctrl+E` (go to end of line).
   - Customizing shortcuts to suit personal workflows.

7. **Understanding Hardware Components:**
   - Familiarizing yourself with basic components like CPU, RAM, storage (SSD/HDD), and input/output devices.
   - Differentiating between hardware and software issues using diagnostic techniques.
   - Learning the function of peripherals (e.g., printers, scanners) and their drivers.
   - Exploring the basic architecture of a computer system and how components interact.

8. **Using Virtualization Software:**
   - Installing and configuring tools like VirtualBox or VMware to create virtual machines.
   - Understanding the purpose and advantages of virtual environments in cybersecurity.
   - Creating snapshots and restoring virtual machine states to save progress or revert changes.
   - Practicing with multiple operating systems simultaneously within a virtualized environment.
   - Understanding the purpose of virtual machines.
   - Creating snapshots and restoring virtual machine states.

## 2. Internet Basics

Mastering the fundamentals of how the internet operates is crucial for understanding cybersecurity principles. This section covers the key concepts that enable secure and effective communication over networks.

### Topics to Learn:

1. **How Data Travels on the Internet:**
   - Understanding the journey of data packets from source to destination, including encapsulation and decapsulation processes.
   - Exploring the OSI and TCP/IP models to understand how layers like application, transport, and network work together.
   - Learning about routers, switches, and gateways and their roles in directing data traffic.
   - Analyzing how data flows through ISPs, servers, and end-user devices.

2. **IP Addresses and DNS:**
   - Distinguishing between IPv4 and IPv6, including addressing schemes and subnetting.
   - Exploring the role of the Domain Name System (DNS) in translating domain names into IP addresses.
   - Understanding DNS records like A, AAAA, MX, and CNAME.
   - Recognizing DNS-related vulnerabilities, such as DNS spoofing and cache poisoning.
   - Configuring and troubleshooting DNS settings on local systems.

3. **HTTP/HTTPS Protocols:**
   - Understanding the structure of HTTP requests and responses, including methods like GET, POST, PUT, and DELETE.
   - Exploring HTTPS and the role of SSL/TLS certificates in establishing secure connections.
   - Identifying common HTTP status codes (e.g., 200, 404, 500) and their meanings.
   - Examining headers, cookies, and session data in HTTP/HTTPS traffic.

4. **Network Protocols:**
   - Learning about key protocols like TCP, UDP, and ICMP, and their characteristics.
   - Understanding the use of protocols like ARP (Address Resolution Protocol) and DHCP (Dynamic Host Configuration Protocol).
   - Exploring secure protocols like SSH, SFTP, and FTPS and their applications.
   - Analyzing the role of SNMP (Simple Network Management Protocol) in monitoring and managing network devices.

5. **Common Internet Security Threats:**
   - Identifying phishing attacks and strategies for avoiding them.
   - Recognizing man-in-the-middle (MITM) attacks and understanding how HTTPS mitigates them.
   - Understanding spoofing, including IP spoofing and email spoofing.
   - Exploring DoS/DDoS attacks and basic mitigation techniques.
   - Analyzing the role of firewalls and intrusion detection/prevention systems in defending against threats.

6. **Networking Tools:**
   - Familiarizing yourself with `ping` and `traceroute` for network diagnostics.
   - Exploring tools like Wireshark for packet analysis and understanding traffic flows.
   - Learning about browser-based tools like DevTools for inspecting and debugging HTTP traffic.
   - Using command-line utilities like `netstat`, `ipconfig`/`ifconfig`, and `nslookup` for network troubleshooting.
   - Practicing with tools like Nmap for network scanning and enumeration.

7. **Wireless Networking Basics:**
   - Understanding Wi-Fi standards and encryption protocols (e.g., WPA2, WPA3).
   - Analyzing the role of access points and SSIDs in wireless networks.
   - Exploring common vulnerabilities in wireless networks, such as weak passwords and rogue access points.
   - Learning how wireless devices communicate through channels and frequencies.

8. **Introduction to Cloud Networking:**
   - Understanding the basic architecture of cloud services and virtual networks.
   - Learning about common cloud providers (e.g., AWS, Azure, Google Cloud) and their network configurations.
   - Recognizing potential security challenges in cloud environments.

## 3. Linux Fundamentals

Linux is a cornerstone of the cybersecurity world. Learning its basics will prepare you for system administration, scripting, and ethical hacking tasks.

### Topics to Learn:

1. **Linux File System:**
   - Understanding the hierarchical structure of the Linux file system (e.g., /bin, /etc, /home, /var).
   - Navigating the file system using commands like `ls`, `cd`, `pwd`, and `tree`.
   - Differentiating between absolute and relative paths.
   - Understanding file permissions and ownership.

2. **Basic Linux Commands:**
   - Using essential commands for file manipulation, such as `cp`, `mv`, `rm`, and `touch`.
   - Viewing file contents with `cat`, `less`, `more`, and `tail`.
   - Searching for files using `find` and `locate` commands.
   - Viewing disk usage with `df` and `du`.

3. **User and Group Management:**
   - Understanding user roles and their importance in system security.
   - Adding and managing users with commands like `adduser` and `usermod`.
   - Setting and changing file permissions with `chmod`, `chown`, and `chgrp`.

4. **Package Management:**
   - Installing, updating, and removing software packages using tools like `apt`, `yum`, or `pacman`.
   - Adding repositories and managing dependencies.
   - Understanding package files (.deb, .rpm) and their installation.

5. **Linux Scripting Basics:**
   - Writing simple shell scripts to automate repetitive tasks.
   - Understanding variables, loops, and conditional statements.
   - Running scripts with appropriate permissions and shebang (`#!/bin/bash`).

6. **System Monitoring and Management:**
   - Checking system performance with tools like `top`, `htop`, and `vmstat`.
   - Monitoring network activity using `netstat` and `ss`.
   - Managing processes with `ps`, `kill`, and `jobs`.

7. **Understanding Logs:**
   - Locating system logs in `/var/log` (e.g., `syslog`, `auth.log`, `dmesg`).
   - Using tools like `tail` and `grep` to analyze log files.
   - Recognizing log rotation and its importance.

8. **Networking Basics in Linux:**
   - Configuring network interfaces with `ifconfig` or `ip` commands.
   - Testing connectivity with `ping` and `traceroute`.
   - Using `curl` and `wget` for downloading and testing web services.
   - Managing firewall settings with `iptables` or `ufw`.

By understanding Linux fundamentals, you will build a strong foundation for tackling more complex cybersecurity challenges.

## 4. Networking Basics:

Understanding networking fundamentals is essential for grasping how devices communicate and how networks are structured. This section covers the basic building blocks of networking.

### Topics to Learn:

1. **What is Networking?**
   - Understanding the basic concept of networking: how devices communicate over shared media.
   - The role of networking in connecting computers, servers, and other devices.
   - Differentiating between physical and logical networks.

2. **Types of Networks:**
   - **LAN (Local Area Network)**: A network that connects devices within a limited area, like a home or office.
   - **WAN (Wide Area Network)**: A network that spans large geographical areas, often used by businesses to connect remote offices.
   - **MAN (Metropolitan Area Network)**: Larger than LAN but smaller than WAN, typically covering a city or region.
   - **PAN (Personal Area Network)**: A small network, typically for personal devices like smartphones and laptops.

3. **Key Network Devices:**
   - **Router**: A device that forwards data between networks.
   - **Switch**: A device that connects devices within a single network and directs data to specific devices based on MAC addresses.
   - **Access Point (AP)**: A device that allows wireless devices to connect to a wired network.
   - **Firewall**: A device or software that monitors and controls incoming and outgoing network traffic based on security rules.

4. **IP Addressing Basics:**
   - Understanding the structure of an IP address, including the difference between IPv4 and IPv6.
   - Explanation of **Private** and **Public IP addresses** and their usage.
   - The role of **Subnetting** in dividing networks and managing IP address allocation.

5. **Understanding the OSI and TCP/IP Models:**
   - The OSI Model: Divides networking tasks into 7 layers (Physical, Data Link, Network, Transport, Session, Presentation, and Application).
   - TCP/IP Model: A 4-layer model that simplifies the OSI model into layers (Link, Internet, Transport, Application).
   - Comparison between the OSI and TCP/IP models to understand their practical use.

6. **Common Networking Protocols:**
   - **TCP (Transmission Control Protocol)**: A connection-oriented protocol that ensures reliable communication between devices.
   - **UDP (User Datagram Protocol)**: A faster but less reliable protocol used for real-time communications.
   - **ICMP (Internet Control Message Protocol)**: Used for sending error messages and operational information about IP operations (e.g., `ping` command).
   - **ARP (Address Resolution Protocol)**: Resolves IP addresses to MAC addresses within a local network.

7. **Understanding DNS (Domain Name System):**
   - The role of DNS in mapping human-readable domain names (like `www.example.com`) to IP addresses.
   - DNS record types such as **A**, **AAAA**, **MX**, and **CNAME** and their respective functions.
   - DNS security concerns, including **DNS spoofing** and **cache poisoning**.

8. **How Data Travels on the Internet:**
   - Understanding the process of data transmission across networks using packets.
   - The role of **routers**, **switches**, and **gateways** in directing traffic between devices.
   - Exploring how data is encapsulated and decapsulated as it moves through the OSI and TCP/IP layers.

9. **Network Topologies:**
   - **Bus Topology**: All devices are connected to a single central cable, or bus.
   - **Star Topology**: Devices are connected to a central hub or switch.
   - **Ring Topology**: Devices are connected in a circular fashion, where data travels in one direction.
   - **Mesh Topology**: Devices are interconnected, providing multiple paths for data to travel.

10. **Basic Networking Tools:**
    - **Ping**: A tool to test the reachability of a device on a network.
    - **Traceroute**: Traces the path that data takes from the source to the destination.
    - **Netstat**: A command-line tool that displays network connections, routing tables, and interface statistics.
    - **Nslookup**: A tool used to query DNS records and troubleshoot DNS issues.
    - **Wireshark**: A packet-sniffing tool used to capture and analyze network traffic.

11. **Introduction to Wireless Networking:**
    - Understanding **Wi-Fi** standards (802.11a/b/g/n/ac/ax) and their differences.
    - The role of **Access Points (AP)** and **SSID** in setting up wireless networks.
    - Common vulnerabilities in wireless networks, such as **WEP**, **WPA**, and **WPA2** encryption weaknesses.

12. **Network Security Fundamentals:**
    - Understanding basic security measures like **firewalls**, **VPNs (Virtual Private Networks)**, and **intrusion detection systems (IDS)**.
    - Recognizing common attacks like **DDoS (Distributed Denial of Service)**, **MITM (Man-in-the-Middle)**, and **phishing**.
    - Introduction to secure communication protocols such as **HTTPS**, **SSH**, and **SFTP**.
    
By grasping these foundational networking concepts, you will gain a solid understanding of how networks operate and how to secure them against common threats.

## 5. Cybersecurity Basics:

Understanding cybersecurity fundamentals is critical for protecting systems, networks, and data from unauthorized access, attacks, and damage. This section covers the foundational principles of cybersecurity.

### Topics to Learn:

1. **What is Cybersecurity?**
   - Definition and importance of cybersecurity in protecting digital assets.
   - Overview of the different domains of cybersecurity (e.g., network security, information security, application security).
   - The concept of **confidentiality**, **integrity**, and **availability** (CIA triad).

2. **Types of Cybersecurity Threats:**
   - **Malware**: Software designed to disrupt or damage systems, including viruses, worms, and Trojans.
   - **Phishing**: Deceptive attempts to acquire sensitive information through fraudulent emails, websites, or messages.
   - **Ransomware**: Malicious software that encrypts files or locks users out of their systems until a ransom is paid.
   - **Social Engineering**: Manipulating individuals into revealing confidential information through psychological manipulation.
   - **DDoS (Distributed Denial of Service) Attacks**: Overloading a system or network with traffic to cause a service disruption.

3. **Network Security Fundamentals:**
   - Understanding how to protect network devices (routers, switches, firewalls) from unauthorized access.
   - Configuring **firewalls** to filter out malicious traffic and protect the internal network.
   - The role of **VPNs (Virtual Private Networks)** in securing remote communications.
   - Securing Wi-Fi networks using **WPA2** or **WPA3** encryption to prevent unauthorized access.

4. **Authentication and Authorization:**
   - The difference between **authentication** (verifying identity) and **authorization** (granting permission).
   - Types of authentication methods: **Password-based**, **Multi-factor Authentication (MFA)**, and **Biometrics**.
   - Understanding **Access Control Models** (e.g., DAC, MAC, RBAC).
   - The principle of **least privilege** in granting users only the permissions they need.

5. **Data Security and Encryption:**
   - Importance of **data protection** and encryption in securing sensitive information.
   - Symmetric vs. Asymmetric encryption and their use cases.
   - Understanding **SSL/TLS** protocols for encrypting communication over the web.
   - Best practices for **data backup** and **disaster recovery**.

6. **Incident Response and Management:**
   - The process of identifying, responding to, and mitigating cybersecurity incidents.
   - Understanding the importance of having an **Incident Response Plan (IRP)** in place.
   - Steps in the incident response lifecycle: **Preparation**, **Detection**, **Containment**, **Eradication**, **Recovery**, and **Lessons Learned**.
   - The role of **forensics** in investigating cybersecurity incidents.

7. **Common Security Vulnerabilities:**
   - **SQL Injection**: A code injection attack that exploits vulnerabilities in a web application's database layer.
   - **Cross-Site Scripting (XSS)**: An attack that injects malicious scripts into web pages viewed by other users.
   - **Buffer Overflow**: A vulnerability that occurs when a program writes more data to a buffer than it can handle, leading to potential system compromise.
   - **Privilege Escalation**: Exploiting weaknesses in a system to gain higher access rights or privileges.

8. **Security Best Practices:**
   - **Patch Management**: Regularly updating software and systems to fix security vulnerabilities.
   - **Strong Password Policies**: Using complex, unique passwords and encouraging regular password changes.
   - **Network Segmentation**: Dividing a network into segments to limit the impact of a breach.
   - **Least Privilege**: Restricting user access to only the information and systems they need to perform their job functions.

9. **Cybersecurity Frameworks and Standards:**
   - Understanding well-known cybersecurity frameworks such as **NIST**, **ISO/IEC 27001**, and **CIS Controls**.
   - Introduction to regulatory standards like **GDPR** (General Data Protection Regulation) and **HIPAA** (Health Insurance Portability and Accountability Act) that govern data protection.
   - The importance of compliance in maintaining a secure environment.

10. **Social Engineering and Human Factors:**
    - The role of human error and manipulation in security breaches.
    - Types of social engineering attacks: **Phishing**, **Pretexting**, **Baiting**, and **Tailgating**.
    - Educating employees and individuals about security awareness and best practices to mitigate human-based risks.

11. **Ethical Hacking and Penetration Testing:**
    - The role of ethical hackers in identifying vulnerabilities and strengthening security defenses.
    - Introduction to penetration testing: the process of simulating attacks on systems to discover weaknesses.
    - Tools used in penetration testing, including **Nmap**, **Metasploit**, and **Wireshark**.

12. **Cybersecurity Tools and Technologies:**
    - **Antivirus and Anti-malware Software**: Tools that detect and protect systems from malware infections.
    - **Intrusion Detection Systems (IDS)** and **Intrusion Prevention Systems (IPS)**: Tools that monitor network traffic for signs of malicious activity.
    - **Security Information and Event Management (SIEM)**: Systems that aggregate and analyze security data from across an organization.
    - **Firewalls**: Hardware or software that filters and controls incoming and outgoing network traffic based on predetermined security rules.

By mastering these cybersecurity basics, you will gain a solid understanding of how to protect systems, networks, and sensitive data from evolving threats.

## 6. Ethical Hacking Principles:

Ethical hacking is a critical practice in cybersecurity, where professionals use hacking techniques to find vulnerabilities and weaknesses in systems, with the goal of improving security. This section covers the foundational principles that guide ethical hacking practices.

### Topics to Learn:

1. **What is Ethical Hacking?**
   - Definition of ethical hacking: the practice of testing systems for vulnerabilities to help secure them.
   - The role of ethical hackers in finding and reporting security flaws to organizations.
   - Distinguishing between ethical hacking and illegal hacking (black-hat vs. white-hat hackers).
   - Understanding the importance of **consent** and **authorization** before performing security assessments.

2. **The Ethical Hacking Process:**
   - **Reconnaissance (Information Gathering)**: Collecting information about the target system or network through public sources and techniques like **OSINT** (Open-Source Intelligence).
   - **Scanning and Enumeration**: Identifying active hosts, open ports, services, and potential vulnerabilities in a system.
   - **Gaining Access**: Using techniques to exploit vulnerabilities and gain unauthorized access to a system.
   - **Maintaining Access**: Creating a foothold in the system for future exploitation or persistence.
   - **Clearing Tracks**: Removing traces of exploitation to avoid detection by the system administrator (important for penetration testing only).
   - **Reporting**: Documenting findings and providing recommendations for improving security.

3. **Key Ethical Hacking Tools:**
   - **Nmap**: A tool for network scanning and port discovery.
   - **Metasploit**: A framework for exploiting vulnerabilities and performing penetration testing.
   - **Wireshark**: A network protocol analyzer for capturing and analyzing network traffic.
   - **Burp Suite**: A suite of tools for testing web application security, including vulnerability scanning and intercepting HTTP traffic.
   - **John the Ripper**: A password cracking tool for identifying weak passwords.
   - **Nikto**: A web server scanner that identifies potential security issues in websites.

4. **Legal and Ethical Considerations:**
   - **Authorization**: Ensuring written consent from the target organization before performing any penetration testing or vulnerability assessment.
   - **Non-Disclosure Agreements (NDA)**: Protecting sensitive information and findings by signing NDAs before engaging in ethical hacking projects.
   - **Compliance and Regulations**: Understanding laws like **Computer Fraud and Abuse Act (CFAA)**, **GDPR**, and others that govern ethical hacking practices.
   - **Ethical Responsibilities**: The importance of transparency, honesty, and professionalism when reporting vulnerabilities.

5. **Types of Ethical Hacking:**
   - **White-Hat Hacking**: Ethical hackers who work with organizations to find and fix vulnerabilities.
   - **Black-Hat Hacking**: Malicious hackers who exploit vulnerabilities for personal gain or harm (illegal).
   - **Gray-Hat Hacking**: Hackers who may find vulnerabilities without authorization but report them to the affected organization (often without malicious intent).
   - **Red Teaming**: A simulated attack on an organization to test its defenses, typically involving a full-scale penetration test.
   - **Blue Teaming**: The defensive counterpart to red teaming, focused on detecting and defending against cyberattacks.

6. **Reconnaissance and Footprinting:**
   - The importance of gathering as much information as possible about a target before attempting any penetration.
   - **Passive Reconnaissance**: Gathering information without directly interacting with the target system (e.g., searching for public information on social media, WHOIS databases).
   - **Active Reconnaissance**: Directly interacting with the target system to gather information (e.g., pinging servers, scanning for open ports).
   - Using tools like **WHOIS**, **NSLookup**, and **Google Dorking** for information gathering.

7. **Vulnerability Assessment:**
   - Scanning systems for known vulnerabilities using tools like **Nessus** or **OpenVAS**.
   - Identifying common vulnerabilities such as **SQL Injection**, **Cross-Site Scripting (XSS)**, **Buffer Overflow**, and **Privilege Escalation**.
   - The process of identifying and evaluating potential threats and weaknesses in systems and applications.
   - Understanding the difference between a vulnerability scan and a penetration test.

8. **Social Engineering in Ethical Hacking:**
   - The role of social engineering in manipulating people into revealing sensitive information or performing actions that compromise security.
   - Common techniques like **phishing**, **pretexting**, **baiting**, and **tailgating**.
   - Ethical considerations and the importance of gaining explicit consent for social engineering assessments.
   - The impact of human behavior on security and how social engineering can bypass technical defenses.

9. **Post-Exploitation Techniques:**
   - Once access is gained, maintaining access and gathering further intelligence about the system and network.
   - **Privilege Escalation**: Techniques to elevate user privileges within the compromised system.
   - **Pivoting**: Using a compromised system to access other systems or networks.
   - **Exfiltration**: Techniques to extract sensitive data from the compromised system, while remaining undetected.

10. **Reporting and Documentation:**
    - The importance of clear, concise, and professional documentation when reporting findings.
    - **Executive Summary**: High-level overview of findings for non-technical stakeholders.
    - **Technical Report**: Detailed technical description of vulnerabilities, exploitation methods, and remediation steps.
    - **Remediation**: Offering actionable advice to help fix vulnerabilities and improve security posture.

11. **Security Awareness and Education:**
    - The importance of educating employees and stakeholders about security risks and best practices.
    - Promoting a **Security-first** mindset in organizations, including training on social engineering, phishing, and password policies.
    - Using penetration testing findings to drive continuous improvement in security awareness programs.

12. **Ethical Hacking Certifications:**
    - Introduction to certifications that validate skills and knowledge in ethical hacking, such as:
      - **Certified Ethical Hacker (CEH)**.
      - **Offensive Security Certified Professional (OSCP)**.
      - **CompTIA Security+**.
      - **Certified Penetration Testing Engineer (CPTE)**.

By understanding and applying these ethical hacking principles, you can contribute to enhancing the security of systems and networks while adhering to legal, ethical, and professional standards.

## 7. Tools for Beginners
work in progress

## 8. Introduction to Scripting
work in progress

## 9. Cyber Hygiene Practices
work in progress
