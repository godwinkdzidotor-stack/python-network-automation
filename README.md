# Python Network & Security Automation

This repository contains Python tools for automating basic network and security tasks.

## 🔧 Tools Included

### **1. firewall_audit.py**
Reads firewall CSV rule files and flags overly permissive rules:
- `src = any`
- `dst = any`
- `0.0.0.0/0` inbound rules
- Wide allow rules

Useful for quick firewall audits and security assessments.

---

### **2. subnet_scan.py**
Simple ICMP reachability scanner for a subnet:
- Walks all hosts in a CIDR
- Sends one ping per host
- Reports reachable hosts

Great for learning and basic troubleshooting.

---

## 📁 Repository Structure

