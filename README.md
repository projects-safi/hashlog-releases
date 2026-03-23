# 🛡️ HashLog: The Anti-MDM Compliance Agent

**Endpoint compliance without the corporate spyware.**

HashLog is the privacy-first compliance agent for BYOD (Bring Your Own Device) engineering teams. It allows remote developers to cryptographically prove their machine is secure for SOC 2, HIPAA, ISO 27001, and GDPR audits—_without_ granting IT root access, installing kernel extensions, or giving up control of their personal Macs.

![HashLog Status](https://img.shields.io/badge/macOS-12.0+-00E5CC?style=for-the-badge&logo=apple)
![License](https://img.shields.io/badge/License-Proprietary-7B61FF?style=for-the-badge)

---

## 🚀 Download & Installation

1. Go to the [Releases Page](../../releases/latest).
2. Download the latest `HashLog_X.X.X.dmg` for your Mac architecture (Apple Silicon or Intel).
3. Open the `.dmg` and drag HashLog to your Applications folder.
4. Launch HashLog. It will run silently in your macOS Menu Bar.
5. Open the Dashboard from the Menu Bar and enter your Team's Join Code or your Pro License Key.

---

## ✨ Why HashLog? (The Privacy Promise)

Traditional MDMs (like Jamf) and compliance agents (like Vanta) require invasive root privileges. HashLog operates on a **"Zero-Root, Zero-Trust"** philosophy.

- **🚫 We Never:** Read files outside your Work Boundaries, record your screen, require Full Disk Access, or upload your source code.
- **✅ We Always:** Scan only the folders you explicitly authorize, sign compliance receipts mathematically using your device's local Ed25519 private key, and let you inspect the exact JSON payload before it syncs to your CTO.

### Core Capabilities

- **Automated Security Baselines:** Natively verifies FileVault, OS Firewall, SIP, screen auto-lock, and open `LISTEN` ports.
- **Local Git Secret Scanning:** Detects hardcoded AWS keys and PII in your commit history locally.
- **Real-Time Leak Detection:** Fires native macOS alerts if a sensitive file is dragged outside your managed boundary.
- **Application Posture (EDR):** Audits installed applications for critical vulnerabilities and unauthorized AI extensions (VS Code).

---

_For support or to purchase a Team/Pro license, visit [hashlog.dev](https://hashlog.dev)._
