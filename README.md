
# 🛡️ Mini SOC Lab: Splunk Threat Detection

Welcome to the **Mini SOC Lab**! This repository features 7 practical projects for analyzing different network logs using Splunk SIEM, designed to build your skills in threat detection and incident response.

---

## 🚀 Projects Overview

| # | Project | Focus | Visual Flow |
|---|---------|-------|-------------|
| 1 | [Analyzing DNS Logs](#1-analyzing-dns-logs) | Detecting malicious domains | ![DNS](https://img.icons8.com/color/48/000000/domain.png) |
| 2 | [Analyzing FTP Logs](#2-analyzing-ftp-logs) | Suspicious file transfers | ![FTP](https://img.icons8.com/color/48/000000/ftp.png) |
| 3 | [Analyzing HTTP Logs](#3-analyzing-http-logs) | Web attack detection | ![HTTP](https://img.icons8.com/color/48/000000/web.png) |
| 4 | [Analyzing SSH Logs](#4-analyzing-ssh-logs) | Brute force & unauthorized access | ![SSH](https://img.icons8.com/color/48/000000/console.png) |
| 5 | [Analyzing Tunnel Logs](#5-analyzing-tunnel-logs) | VPN/tunnel anomalies | ![VPN](https://img.icons8.com/color/48/000000/vpn.png) |
| 6 | [Analyzing SMTP Logs](#6-analyzing-smtp-logs) | Phishing & spam | ![SMTP](https://img.icons8.com/color/48/000000/send-mass-email.png) |
| 7 | [Analyzing DHCP Logs](#7-analyzing-dhcp-logs) | Rogue device detection | ![DHCP](https://img.icons8.com/color/48/000000/network-card.png) |

---

## 📚 Table of Contents

1. [Project 1: DNS Logs](#1-analyzing-dns-logs)
2. [Project 2: FTP Logs](#2-analyzing-ftp-logs)
3. [Project 3: HTTP Logs](#3-analyzing-http-logs)
4. [Project 4: SSH Logs](#4-analyzing-ssh-logs)
5. [Project 5: Tunnel Logs](#5-analyzing-tunnel-logs)
6. [Project 6: SMTP Logs](#6-analyzing-smtp-logs)
7. [Project 7: DHCP Logs](#7-analyzing-dhcp-logs)

---

## 📝 Project Details

### 1. Analyzing DNS Logs
**Goal:** Detect suspicious/malicious domain queries.

**Flow:**
```
User → DNS Query → DNS Server → Splunk → Threat Detection
```
**Reference:** [Splunk DNS Analytics](https://www.splunk.com/en_us/blog/security/dns-analytics-for-threat-detection.html)

---

### 2. Analyzing FTP Logs
**Goal:** Identify unauthorized file transfers and brute force attempts.

**Flow:**
```
User ↔ FTP Server → Splunk → Suspicious Activity Detection
```
**Reference:** [Splunk FTP Log Analysis](https://community.splunk.com/t5/Security/FTP-log-analysis-in-Splunk/m-p/527839)

---

### 3. Analyzing HTTP Logs
**Goal:** Detect web attacks (XSS, SQLi, etc.) and abnormal traffic.

**Flow:**
```
Browser → HTTP Request → Web Server → Splunk → Web Attack Detection
```
**Reference:** [Splunk HTTP Event Collector](https://docs.splunk.com/Documentation/Splunk/latest/Data/UsetheHTTPEventCollector)

---

### 4. Analyzing SSH Logs
**Goal:** Monitor for brute force and unauthorized SSH access.

**Flow:**
```
User → SSH Login Attempt → SSH Server → Splunk → Access Detection
```
**Reference:** [Splunk SSH Security Monitoring](https://www.splunk.com/en_us/blog/security/ssh-security-monitoring.html)

---

### 5. Analyzing Tunnel Logs
**Goal:** Detect VPN/tunnel misuse and anomalies.

**Flow:**
```
User → VPN/Tunnel Connection → Tunnel Server → Splunk → Anomaly Detection
```
**Reference:** [Splunk VPN Log Analysis](https://community.splunk.com/t5/Security/VPN-log-analysis/m-p/527840)

---

### 6. Analyzing SMTP Logs
**Goal:** Identify phishing, spam, and email-based threats.

**Flow:**
```
User → Email Sent/Received → SMTP Server → Splunk → Threat Detection
```
**Reference:** [Splunk Email Security Analytics](https://www.splunk.com/en_us/blog/security/email-security-analytics.html)

---

### 7. Analyzing DHCP Logs
**Goal:** Detect rogue devices and abnormal DHCP activity.

**Flow:**
```
Device → DHCP Request → DHCP Server → Splunk → Rogue Device Detection
```
**Reference:** [Splunk DHCP Log Analysis](https://community.splunk.com/t5/Security/DHCP-log-analysis-in-Splunk/m-p/527841)

---

## 📦 How to Use

1. Clone this repository.
2. Follow the instructions in each project markdown file.
3. Use the provided Splunk queries and diagrams to guide your analysis.

---

## 🌐 More Resources

- [Splunk Security Essentials](https://splunkbase.splunk.com/app/3435/)
- [Splunk Security Blog](https://www.splunk.com/en_us/blog/security.html)

---

<div align="center">
	<b>Happy Threat Hunting! 🕵️‍♂️</b>
</div>

# Splunk SIEM Log Analysis Projects

**Maintained by: Kirubakaran Venkatesan**

This repository contains a collection of projects for analyzing various types of logs using Splunk SIEM. Each project provides a structured guide for uploading sample log files, performing analysis, and gaining insights into specific types of log data.

## Projects

1. Analyzing DNS Logs Using Splunk SIEM: This project provides a step-by-step guide for analyzing DNS (Domain Name System) log files using Splunk SIEM. It covers uploading sample log files, extracting relevant fields, analyzing DNS query patterns, detecting anomalies, and monitoring DNS traffic.
2. Analyzing FTP Logs Using Splunk SIEM: This project guides you through analyzing FTP (File Transfer Protocol) log files using Splunk SIEM. It includes steps for uploading sample log files, extracting fields, analyzing FTP activity patterns, detecting anomalies, and monitoring FTP traffic.
3. Analyzing HTTP Logs Using Splunk SIEM: This project outlines the process of analyzing HTTP (Hypertext Transfer Protocol) log files using Splunk SIEM. It covers uploading sample log files, extracting relevant fields, analyzing HTTP request patterns, detecting anomalies, and monitoring HTTP traffic.
4. Analyzing SSH Logs Using Splunk SIEM: This project provides a comprehensive guide for analyzing SSH (Secure Shell) log files using Splunk SIEM. It includes steps for uploading sample log files, extracting fields, analyzing SSH activity patterns, detecting anomalies, and correlating SSH logs with other data sources.
5. Analyzing Tunnel Logs Using Splunk SIEM: This project demonstrates how to analyze tunnel log traffic (e.g., GRE, IPv4, IPv6) from Zeek IDS using Splunk SIEM. It covers uploading sample log files, performing analysis, detecting anomalies, and correlating tunnel logs with other logs for enhanced threat detection.
6. Analyzing SMTP Logs Using Splunk SIEM: This project provides a structured approach for analyzing SMTP (Simple Mail Transfer Protocol) log files using Splunk SIEM. It includes steps for uploading sample log files, extracting fields, analyzing email traffic patterns, detecting anomalies, and monitoring SMTP activity.
7. Analyzing DHCP Logs Using Splunk SIEM: This project offers guidance on analyzing DHCP (Dynamic Host Configuration Protocol) log files using Splunk SIEM. It covers uploading sample log files, extracting fields, analyzing IP address assignments, detecting anomalies, and monitoring DHCP traffic.
