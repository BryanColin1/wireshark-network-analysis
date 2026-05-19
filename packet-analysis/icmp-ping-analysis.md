# ICMP Ping Traffic Analysis

## Objective

Analyze ICMP ping traffic generated from a Kali Linux VM to `example.com` and explain the purpose of ICMP Echo Request and Echo Reply packets.

## Environment

| Component | Description |
|---|---|
| Capture Machine | Kali Linux VM |
| Tool | Wireshark |
| Network Mode | NAT |
| Source IP | `10.0.2.15` |
| Destination | `example.com` |
| Resolved Destination IP | `172.66.147.243` |

## Command Used

```bash
ping example.com
