# 🔬 OBinwalk

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OBinwalk** is a powerful binary forensic analyzer. It performs magic signature scanning, entropy analysis, PE/ELF parsing, string extraction, IOC detection, and polyglot identification with low memory usage and streaming support.

---

## 📌 Overview

OBinwalk is designed for malware researchers and digital forensics analysts. It scans binaries of any size (even GBs) efficiently, detects embedded files, calculates entropy zones, extracts IOCs, and provides detailed reports on file structure and suspicious patterns.

**Key Strength**: Bounded memory usage + streaming architecture.

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Scan File**               | Full forensic analysis (signatures, entropy, PE, IOCs) |
| **[2]** | **Batch Scan**              | Scan all files in a directory |
| **[3]** | **Quick Entropy**           | Fast entropy check only |
| **[4]** | **Extract Strings**         | ASCII + UTF-8 + UTF-16LE string extraction |
| **[5]** | **Extract IOCs**            | URLs, IPs, emails, domains, file paths |
| **[6]** | **Last Report**             | View the most recent scan report |
| **[7]** | **Export**                  | Save report as JSON or CSV |
| **[8]** | **Settings**                | Configure chunk size, entropy thresholds, output directory |

---

## 📊 Key Features

- **Magic Signature Scanning** — ELF, PE, PDF, ZIP, JPEG, PNG, GZIP, BZIP2, XZ, Java Class, RTF, OLE, MP3, RIFF, Matroska, etc.
- **Entropy Analysis** — Global + local high-entropy zones (packed/encrypted detection)
- **PE/ELF Parsing** — Architecture, sections, compilation timestamp, section entropy
- **String Extraction** — ASCII, UTF-8, UTF-16LE with preview
- **IOC Extraction** — URLs, IPs, emails, domains, file paths
- **Polyglot Detection** — Multiple file types embedded in one binary
- **Low Memory Streaming** — Processes large files efficiently
- **Detailed Reports** — JSON export with full forensic metadata

---

## ⚙️ Requirements

- **Linux or Windows**
- **No additional dependencies** — pure Python with standard library

---

## 🚀 Usage

```bash
./OBinwalk

📁 Output

Rich Terminal Report — Colored signatures, entropy gauge, PE details, IOC summary
JSON Export — Complete forensic report with all metadata
CSV Export — Batch summary with entropy, signatures, and hashes
Entropy Zones — List of high-entropy regions (packed/encrypted indicators)


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED FORENSIC ANALYSIS & MALWARE RESEARCH USE ONLY
