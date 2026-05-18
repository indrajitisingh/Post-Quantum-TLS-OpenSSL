# Post-Quantum Cryptography Based TLS Communication

## Project Overview

This project demonstrates the implementation of Post-Quantum Cryptography (PQC) in TLS communication using OpenSSL, liboqs, and the OQS Provider on Ubuntu Linux running inside VMware.

The project focuses on integrating quantum-safe cryptographic algorithms into TLS communication and analyzing the handshake process using Wireshark packet capture.

---

## Objective

The objective of this project was:

- To understand the impact of quantum computing on classical cryptography
- To implement PQC-enabled TLS communication
- To compare Classical TLS and PQC-based TLS
- To analyze TLS packets using Wireshark
- To study future-ready cybersecurity mechanisms

---

##Technologies Used

| Tool / Technology | Purpose |
|---|---|
| Ubuntu Linux | Operating System |
| VMware | Virtual Environment |
| OpenSSL 3.x | TLS Communication |
| liboqs | PQC Algorithm Library |
| OQS Provider | PQC Integration with OpenSSL |
| Wireshark | Packet Analysis |
| CMake | Build Configuration |
| Ninja | Build System |

---

## Project Features

- PQC-enabled TLS communication
- TLS client-server implementation
- Certificate generation using OpenSSL
- Wireshark packet analysis
- TLS handshake inspection
- Classical TLS vs PQC TLS comparison
- Secure encrypted communication testing

---

## Project Workflow

## 1. Environment Setup

- Ubuntu installed on VMware
- OpenSSL configured
- liboqs installed
- OQS Provider integrated with OpenSSL

---

## 2. TLS Certificate Generation

Generated:
- Server private key
- Certificate Signing Request (CSR)
- Self-signed certificate

Commands used:

```bash
openssl genpkey -algorithm RSA -out server.key```
