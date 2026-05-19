# Wireshark Network Analysis

## Overview

This project demonstrates basic network traffic analysis using Wireshark in a controlled lab environment. The objective is to capture, inspect, and explain common network protocols and identify security-relevant traffic patterns.

## Lab Environment

| Component | Description |
|---|---|
| Capture Machine | Kali Linux VM |
| Target Machine | Metasploitable 2 VM for scanning traffic analysis |
| Network Modes | NAT and VirtualBox Host-Only Network |
| Tools | Wireshark, Nmap, curl, nslookup |

## Objectives

- Capture network traffic using Wireshark
- Analyze common protocols such as ICMP, DNS, TCP, and HTTP
- Identify packet-level behavior for normal and suspicious traffic
- Document observations in a clear security-focused format
- Build practical traffic analysis skills for cybersecurity roles

## Project Structure

```text
wireshark-network-analysis/
├── captures/
├── notes/
│   └── lab-scope.md
├── packet-analysis/
│   ├── dns-analysis.md
│   ├── http-analysis.md
│   ├── icmp-ping-analysis.md
│   ├── suspicious-scanning-traffic.md
│   └── tcp-handshake-analysis.md
├── screenshots/
└── README.md
```

## Analyses Completed

| Analysis | Description |
|---|---|
| [ICMP Ping Analysis](packet-analysis/icmp-ping-analysis.md) | Examines Echo Request and Echo Reply traffic |
| [DNS Query and Response Analysis](packet-analysis/dns-analysis.md) | Shows how a domain name resolves to IP addresses |
| [TCP Three-Way Handshake Analysis](packet-analysis/tcp-handshake-analysis.md) | Explains TCP connection establishment |
| [HTTP Request and Response Analysis](packet-analysis/http-analysis.md) | Shows unencrypted HTTP request and response traffic |
| [Suspicious Scanning Traffic Analysis](packet-analysis/suspicious-scanning-traffic.md) | Demonstrates Nmap SYN scan behavior in Wireshark |

## Skills Demonstrated

Packet capture
Protocol analysis
Network troubleshooting
Traffic interpretation
Security-focused documentation
Reconnaissance traffic identification
GitHub portfolio documentation

## Disclaimer

This project was performed in a controlled lab environment for educational and defensive security purposes only. No unauthorized packet capture or testing was performed against third-party systems.
