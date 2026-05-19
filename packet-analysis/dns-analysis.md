# DNS Query and Response Analysis

## Objective

Analyze DNS traffic generated when resolving `example.com` and explain how a domain name is translated into IP addresses.

## Environment

| Component | Description |
|---|---|
| Capture Machine | Kali Linux VM |
| Tool | Wireshark |
| Network Mode | NAT |
| Source IP | `10.0.2.15` |
| DNS Server | `192.168.1.1` |
| Queried Domain | `example.com` |

## Command Used

```bash
nslookup example.com
