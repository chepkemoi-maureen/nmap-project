# Nmap Vulnerability Scanning Project

##  Objective
This project demonstrates a basic network scan using Nmap to identify open ports, detect service versions, and assess potential vulnerabilities on a test machine. I created as part of my cybersecurity internship preparation to showcase hands-on skills in reconnaissance and documentation.

## Tools Used
- **Operating System:** Ubuntu 22.04
- **Scanner:** Nmap v7.93
- **Target:** Metasploitable2 VM 127.0.0.1

##  Commands
nmap -sV -O 127.0.0.1
nmap -p 1-1000 127.0.0.1
nmap -sS -T4 -oN scan_report.txt 127.0.0.1
