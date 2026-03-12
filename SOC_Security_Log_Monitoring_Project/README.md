
# Security Log Monitoring & Incident Analysis (SOC Lab Simulation)

## Project Overview
This project simulates a **Security Operations Center (SOC) environment** where security logs are collected, analyzed, and investigated for potential threats.

The goal is to demonstrate SOC analyst skills including:
- Log monitoring
- Network traffic analysis
- Incident investigation
- Threat detection

## Tools Used
- Wireshark
- Splunk (SIEM)
- Kali Linux
- Windows Event Logs
- Nmap

## Lab Architecture
Attacker Machine: Kali Linux  
Target Machine: Windows VM  
Monitoring Tool: Splunk + Wireshark

## Project Steps

### 1. Network Scanning Simulation
Using Nmap to scan a target machine.

Example command:
```
nmap -sS -A 192.168.1.10
```

### 2. Capture Network Traffic
Wireshark used to capture packets and detect suspicious activity.

### 3. Log Collection
System and network logs are imported into Splunk.

### 4. Incident Detection
SOC analyst identifies suspicious activities such as:
- Port scanning
- Brute force attempts
- Suspicious IP traffic

### 5. Incident Analysis
Analyze logs and determine attacker behavior.

## Sample Detection Scenarios

### Scenario 1: Port Scan Detection
Detected multiple SYN packets from attacker IP.

### Scenario 2: Brute Force Login Attempt
Multiple failed login attempts detected in logs.

### Scenario 3: Suspicious Network Traffic
Unusual outbound traffic observed in Wireshark.

## Skills Demonstrated
- SIEM Log Analysis
- Threat Detection
- Packet Analysis
- SOC Investigation Workflow

## Author
Dhanraj Karpe

SOC Analyst Project
