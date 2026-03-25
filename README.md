# Mini SOC Lab: Splunk Threat Detection Projects

This repository contains 7 hands-on projects for analyzing various network logs using Splunk SIEM. Each project focuses on a different protocol or log type, helping you understand threat detection in a Security Operations Center (SOC) environment.

## Visual Overview of Each Project

### 1. Analyzing DNS Logs
**Visual:**
```
User → DNS Query → DNS Server → Splunk Log Collection → Threat Detection
```
**Reference:** [Splunk DNS Analytics](https://www.splunk.com/en_us/blog/security/dns-analytics-for-threat-detection.html)

### 2. Analyzing FTP Logs
**Visual:**
```
User ↔ FTP Server (Login/Upload/Download) → Splunk Log Collection → Suspicious Activity Detection
```
**Reference:** [Splunk FTP Log Analysis](https://community.splunk.com/t5/Security/FTP-log-analysis-in-Splunk/m-p/527839)

### 3. Analyzing HTTP Logs
**Visual:**
```
Browser → HTTP Request → Web Server → Splunk Log Collection → Web Attack Detection
```
**Reference:** [Splunk HTTP Event Collector](https://docs.splunk.com/Documentation/Splunk/latest/Data/UsetheHTTPEventCollector)

### 4. Analyzing SSH Logs
**Visual:**
```
User → SSH Login Attempt → SSH Server → Splunk Log Collection → Brute Force/Unauthorized Access Detection
```
**Reference:** [Splunk SSH Security Monitoring](https://www.splunk.com/en_us/blog/security/ssh-security-monitoring.html)

### 5. Analyzing Tunnel Logs
**Visual:**
```
User → VPN/Tunnel Connection → Tunnel Server → Splunk Log Collection → Anomaly Detection
```
**Reference:** [Splunk VPN Log Analysis](https://community.splunk.com/t5/Security/VPN-log-analysis/m-p/527840)

### 6. Analyzing SMTP Logs
**Visual:**
```
User → Email Sent/Received → SMTP Server → Splunk Log Collection → Phishing/Spam Detection
```
**Reference:** [Splunk Email Security Analytics](https://www.splunk.com/en_us/blog/security/email-security-analytics.html)

### 7. Analyzing DHCP Logs
**Visual:**
```
Device → DHCP Request → DHCP Server → Splunk Log Collection → Rogue Device Detection
```
**Reference:** [Splunk DHCP Log Analysis](https://community.splunk.com/t5/Security/DHCP-log-analysis-in-Splunk/m-p/527841)

---
Each project folder contains step-by-step instructions and sample queries to help you get started with Splunk-based threat detection for that log type.

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
