# 🦉 OWordlist

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OPass-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OWordlist** — Hybrid Intelligent Wordlist Engine ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OWordlist is a targeted wordlist generator and manager for authorized password-auditing engagements. It builds custom wordlists from profile inputs, applies mutation and leetspeak rules, and merges, filters and deduplicates existing lists. It runs offline so audit material never leaves the host.

---

## ✨ Features


- Custom wordlist generation from profile keywords and patterns
- Mutation rules (case, leetspeak, affixes, year/number suffixes)
- Merge, filter, sort and deduplicate existing wordlists
- Length and complexity constraints to shape output
- Offline operation for sensitive audit material
- Structured export of generated lists, with a --self-test mode

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OWordlist
./OWordlist --self-test
./OWordlist --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
