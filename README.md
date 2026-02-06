# AI-Assisted Adaptive Firewall with SIEM Analytics

## Problem Statement
Traditional firewalls rely on static rules and signature-based detection, which fail to detect novel attacks and abnormal network behavior.

## Solution Overview
This project implements an AI-assisted adaptive firewall prototype that analyzes network traffic behavior, detects anomalies using machine learning, and provides SIEM-style visibility for security decision-making.

## Tech Stack
- Ubuntu Linux
- Python
- Zeek
- scikit-learn
- FastAPI
- Elastic Stack
- PostgreSQL
- Docker

## Project Status
Day 1: Environment and structure setup completed.



## Day 2 – Network Traffic Collection & Zeek Analysis
- Captured real network traffic using tcpdump
- Processed PCAP using Zeek
- Generated structured logs (conn.log, dns.log, http.log, ssl.log)
- Validated fields required for behavior-based anomaly detection
