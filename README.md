# ARP Spoofing & MITM Attack Demonstration Lab

## Cyber Security in Computing Coursework

This repository contains the practical implementation, analysis, and mitigation of **ARP Spoofing based Man-in-the-Middle (MITM) attacks** performed in a controlled lab environment.

The project demonstrates how attackers exploit the insecure design of the **Address Resolution Protocol (ARP)** to intercept traffic, capture credentials, and manipulate communication between network devices.

---

## Project Overview

This coursework focuses on:

- ARP spoofing / ARP poisoning
- Man-in-the-Middle (MITM) attacks
- credential interception
- traffic sniffing
- Wireshark packet analysis
- risk assessment
- mitigation strategies

The project includes two separate attack demonstrations:

1. **Bettercap-based ARP spoofing attack**
2. **Ettercap-based MITM attack in GNS3**

---

## Tools Used

- **Kali Linux**
- **Bettercap**
- **Ettercap**
- **Wireshark**
- **GNS3**
- **Windows 7 VM**
- **Metasploitable2**
- **Router Simulation**

---

## Attack Demonstration 1

### Bettercap ARP Spoofing Attack

This lab demonstrates:

- subnet probing
- host discovery
- ARP target selection
- ARP cache poisoning
- IP forwarding
- traffic sniffing
- credential capture from DVWA

### Outcome

- successful MITM interception
- HTTP credential capture
- ARP cache manipulation validation

---

## Attack Demonstration 2

### Ettercap + GNS3 Lab

This simulation demonstrates:

- flat LAN MITM scenario
- ARP poisoning
- Telnet credential interception
- packet capture in Wireshark
- ARP table comparison before and after attack

### Outcome

- plaintext Telnet password capture
- successful packet interception
- MITM traffic manipulation

---

## Risk Assessment

| Vulnerability | Severity | Impact |
|---|---|---|
| ARP Spoofing | High | MITM and credential theft |
| HTTP / Telnet | Critical | Plaintext credential exposure |
| Lack of DAI | Medium | No L2 protection |

---

## Mitigation Strategies

- Dynamic ARP Inspection (DAI)
- Static ARP entries
- switch security
- HTTPS / SSH migration
- IDS / HIDS deployment
- user awareness training

---

## Educational Purpose

This project was conducted strictly in an **isolated lab environment for academic and ethical educational purposes only**.

---

## Author

Krish Shrestha  
Cyber Security in Computing  
London Metropolitan University
