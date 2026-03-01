# NerveFilter — APK Safety & Verification

This repository provides resources and commands to verify APK files safely and fix common installation errors.

## Fix “App Not Installed” Error (Step-by-Step Guide)

Complete guide with SHA256 checksum, APK signature verification, ADB install debugging and split APK troubleshooting:

👉 https://nervefilter.com/blog/fix-app-not-installed/

---

## Quick Verification Commands

### Check SHA256 (File Integrity)

Linux / Mac:
`sha256sum filename.apk`

Windows PowerShell:
`Get-FileHash filename.apk -Algorithm SHA256`

---

### Verify APK Signature

`apksigner verify --print-certs filename.apk`

---

### Debug Installation Error via ADB

`adb install filename.apk`

---

Official Website:
https://nervefilter.com
