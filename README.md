# Open Source Audit Project — Apache HTTP Server

**Name:** Deepayan Dey 
**Roll Number:** 24BCY10068 
**Course:** Open Source Software  
**Software Selected:** Apache HTTP Server  

---

## Project Overview

This repository contains my Open Source Software Capstone Project based on the Apache HTTP Server.  

The aim of this project is to study how an open-source software works in a real Linux environment and to understand its structure, functionality, and philosophy. Along with the analysis, I have developed shell scripts to demonstrate practical interaction with the system.

The project combines both theoretical understanding and hands-on Linux experience.

---

## Implemented Scripts

### 🔹 Script 1 — System Identity Report  
This script prints important system-level information such as kernel version, logged-in user, uptime, Linux distribution, and licensing details in a structured format.

---

### 🔹 Script 2 — Package Status Inspector  
This script verifies whether Apache is installed on the system and displays its version and details. It also includes a conditional and case-based description of the software.

---

### 🔹 Script 3 — Directory Audit Tool  
This script checks key Linux directories and reports their size, ownership, and permissions. It helps in understanding how access control works in a system.

---

### 🔹 Script 4 — Log Monitoring Script  
This script scans a given log file and counts occurrences of a keyword such as "error". It also shows recent matching entries, which is useful for identifying system issues or suspicious activity.

---

### 🔹 Script 5 — Manifest Generator  
This is an interactive script that takes user input and generates a custom open-source philosophy statement, which is saved to a text file.

---

## Running the Project

### Requirements
- Linux OS (Kali / Ubuntu / Debian)
- Bash shell
- Apache installed
- sudo privileges (for log analysis)

---

### Steps to Execute

**Clone repository:**
```bash
git clone https://github.com/error404-004/oss-audit-24BCY10068.git
cd oss-audit-24BCY10068
```

**Give execution permissions:**
```bash
chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh
```

**Run scripts:**
```bash
./script1.sh
./script2.sh
./script3.sh
sudo ./script4.sh /var/log/apache2/error.log 
./script5.sh
```

---

## Tools & Concepts Used

- Bash scripting  
- Linux commands (`uname`, `uptime`, `du`, `ls`, `grep`)  
- Conditional statements (`if-else`)  
- Loops (`for`, `while`)  
- Case statements  
- File handling and redirection  

---

## Project Insight

Through this project, I understood how open-source tools like Apache HTTP Server operate within a Linux system. I also explored how logs, permissions, and services play an important role in system administration and basic security monitoring.

---

## Note

This project has been developed as part of an academic assignment and reflects my own understanding of open-source systems and Linux shell scripting.

