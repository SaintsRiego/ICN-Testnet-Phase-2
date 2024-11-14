# ICN Testnet Phase 2 - Node Setup Guide

This repository contains the installation instructions and scripts to run your own node in the ICN Testnet Phase 2.

## Steps to Participate in ICN Testnet Phase 2

1. **Go to**: [https://testnet.icn.global/](https://testnet.icn.global/)
2. **Connect Your Wallet**
3. **Delegate Your ICN Passport to Burner Wallet**
4. **Install the ON Application and Run ON**

### Run Commands:

#### For Windows:
```powershell
powershell -ExecutionPolicy Bypass -Command "try { Invoke-WebRequest -Uri 'https://console.icn.global/downloads/install/start.ps1' -OutFile '.\start.ps1' -UseBasicParsing; & '.\start.ps1' -PrivateKey '<private_key>'} finally { Remove-Item .\start.ps1 -ErrorAction Silentlycontinue
