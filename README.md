# sandhya-E---cyber-security-task-1
Paste this updated content into your `README.md` file:

# Task 1 - Local Network Port Scan

## Objective

The objective of this task is to discover open ports on devices connected to the local network using Nmap. This task helps in understanding network reconnaissance, TCP SYN scanning, and basic cybersecurity concepts related to network exposure and security risks.

---

# Tools Used

* Nmap
* Windows Command Prompt

---

# Commands Used

```bash
ipconfig
nmap -sS 192.168.1.6
nmap -sS 192.168.1.6 -oN scan_results.txt
```

---

# IP Configuration Details

```text
IPv4 Address : 192.168.1.6
Subnet Mask  : 255.255.255.0
Default Gateway : 192.168.1.1
```

---

# Description

In this task, I performed a local network scan using the Nmap tool to identify active devices and open ports within my local network. First, I identified my local IP address using the `ipconfig` command in Windows Command Prompt. After identifying the IP address, I performed a TCP SYN scan using Nmap to discover open ports and services running on my system.

During the scanning process, I observed different open ports and understood the services associated with them. This task helped me understand network reconnaissance, port scanning, and the importance of securing open ports to reduce security risks.

---

# Scan Results

The Nmap scan detected the following open ports:

| Port     | State | Service      |
| -------- | ----- | ------------ |
| 135/tcp  | Open  | msrpc        |
| 139/tcp  | Open  | netbios-ssn  |
| 445/tcp  | Open  | microsoft-ds |
| 5357/tcp | Open  | wsdapi       |
| 7070/tcp | Open  | realserver   |

---

# Security Risks of Open Ports

* Unauthorized access to network services
* Exposure of vulnerable applications
* Increased risk of cyber attacks
* Information leakage

---

# Learning Outcome

By completing this task, I gained hands-on experience in:

* Network reconnaissance
* TCP SYN scanning
* Open port identification
* Basic cybersecurity concepts
* Network security analysis
  

# Repository Contents
cyber-security-task-1/
│
├── README.md
├── scan_results.txt
└── screenshots/
      ├── scan1.png
      ├── scan2.png
      ├── scan3.png
---

# Conclusion

This task helped me understand the basics of network scanning and cybersecurity practices using Nmap. It improved my practical understanding of open ports, network exposure, and security analysis techniques used in cybersecurity.
