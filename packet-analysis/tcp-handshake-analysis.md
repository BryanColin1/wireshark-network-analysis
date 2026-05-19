# TCP Three-Way Handshake Analysis

## Objective

Analyze a TCP three-way handshake and explain how a client establishes a connection with a server.

## Background

TCP uses a three-way handshake to establish a reliable connection before data transfer begins.

The three steps are:

1. SYN
2. SYN-ACK
3. ACK

## Capture Method

Traffic was captured using Wireshark in a controlled lab environment.

## Display Filter Used

```text
tcp.flags.syn == 1
