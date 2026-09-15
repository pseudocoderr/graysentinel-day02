
# GraySentinel — Day 02
## Network Scanning with Masscan and Nmap

**Project:** GraySentinel  
**Day:** 02  
**Focus:** Network Discovery and TCP Port Scanning  
**Network:** `192.168.0.0/24`  
**Tools:** Masscan, Nmap  
**Nmap Version:** 7.99  

---

## 1. Objective

The objective of Day 02 was to perform network reconnaissance against the
authorized `192.168.0.0/24` lab network using Masscan for rapid TCP port
discovery and Nmap for detailed validation.

The exercise demonstrates a two-stage reconnaissance workflow:

1. Rapid port discovery using Masscan.
2. Validation of discovered ports using Nmap.

---

## 2. Scope

The scan covered the private network:

```text
192.168.0.0/24
