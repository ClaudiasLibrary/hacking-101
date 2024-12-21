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

Work in progress....
