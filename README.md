# ARP Security Lab (middleMan)

> **Educational cybersecurity lab only.** This repository demonstrates ARP spoofing/poisoning concepts so that defenders can understand how local-network traffic redirection works and how to recognize and mitigate it.

## Scope

The code is intended only for systems and isolated lab networks that you own or have explicit permission to test. Do not use it against third-party devices or networks.

## What This Lab Demonstrates

- ARP request/response fundamentals
- MAC-address discovery on a local network
- How ARP cache manipulation can redirect traffic
- Restoration of ARP mappings after a controlled exercise
- Why protections such as client isolation, segmentation, static ARP where appropriate, and monitoring matter

## Tech Stack

- Python
- Scapy
- ARP / Ethernet networking fundamentals

## Defensive Learning Goals

A useful follow-up to this lab is to analyze packet captures and identify indicators of ARP spoofing, such as unexpected MAC-address changes, repeated unsolicited ARP replies, or conflicting IP-to-MAC mappings.

## Ethical Use

Use this project only for **authorized security education, defensive research, and controlled lab exercises**.

## Author

**Mehmet Zülfü Deniz**  
Software Developer · IT & Technical Support
