# 🦉 OAttackIQ

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OAttack%20/%20Offensive-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OAttackIQ** — Safely simulate adversary techniques to validate security controls and detection

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OAttackIQ is a lightweight breach-and-attack-simulation (BAS) tool for safely testing whether security controls detect and respond to common adversary behaviours. It exercises benign, controlled techniques so blue teams can validate detection coverage and tune their alerting without causing harm. Results can be saved to a JSON report to track control effectiveness over time.

---

## ✨ Features

- Safe breach-and-attack-simulation of common adversary techniques
- Validates detection and response of existing security controls
- Benign, non-destructive test activity only
- Optional local HTTP server for simulation scenarios
- JSON report export via native save dialog or path entry
- Scripting-friendly --no-pause mode for automation

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OAttackIQ
./OAttackIQ --no-pause
./OAttackIQ --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
