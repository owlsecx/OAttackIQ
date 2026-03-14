<div align="center">

# 🦉 OAttackIQ

**Breach & Attack Simulation Tool**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

*Part of the [OwlSec](https://owlsec.org) Toolkit*
```
██████╗  █████╗ ████████╗████████╗ █████╗  ██████╗██╗  ██╗██╗ ██████╗
██╔═══██╗██╔══██╗╚══██╔══╝╚══██╔══╝██╔══██╗██╔════╝██║ ██╔╝██║██╔═══██╗
██║   ██║███████║   ██║      ██║   ███████║██║     █████╔╝ ██║██║   ██║
██║   ██║██╔══██║   ██║      ██║   ██╔══██║██║     ██╔═██╗ ██║██║▄▄ ██║
╚██████╔╝██║  ██║   ██║      ██║   ██║  ██║╚██████╗██║  ██╗██║╚██████╔╝
 ╚═════╝ ╚═╝  ╚═╝   ╚═╝      ╚═╝   ╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═╝ ╚══▀▀═╝
            Network | DNS | File | Beacon | Payload | Lateral
```

</div>

---

## 📌 Overview

**OAttackIQ** is a Breach & Attack Simulation (BAS) tool designed to safely test how well your security controls detect and respond to real-world attack techniques — without causing any actual harm. All simulations are safe and designed for authorized environments.

---

## 🖥️ Menu Options

| Option | Module | Description |
|--------|--------|-------------|
| `[1]` | Port Scan Simulation | Simulate internal/external port scanning activity |
| `[2]` | Suspicious DNS Queries | Generate DNS queries that mimic C2 or data exfil patterns |
| `[3]` | Suspicious File Creation | Create files that trigger EDR/AV detection rules |
| `[4]` | TCP Beacon Simulation | Simulate periodic TCP beaconing to a target |
| `[5]` | HTTP/HTTPS Beacon | Simulate HTTP/S C2 beacon traffic patterns |
| `[6]` | Safe Payload Generation | Generate harmless payloads to test detection systems |
| `[7]` | Lateral Connectivity Check | Test reachability to internal hosts/segments |
| `[S]` | Save JSON Report | Export simulation results to JSON |
| `[0]` | Exit | Quit OAttackIQ |

---

## 🎯 Use Cases

- Test **SIEM** alerting and detection rules
- Validate **EDR/AV** response to suspicious activity
- Verify **firewall** and **IDS/IPS** effectiveness
- Simulate **C2 beacon** patterns in a safe environment
- Measure **SOC** detection and response times

---

## ⚙️ Requirements

- Linux (any distro)
- The tool is pre-built — no Python installation needed

---

## ⚠️ Legal Disclaimer

> **THIS TOOL IS FOR AUTHORIZED SECURITY TESTING ONLY.**  
> All simulations must be run in environments you own or have explicit written permission to test.  
> Unauthorized use is illegal and unethical.  
> The developer is not responsible for any misuse.

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

> 🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
