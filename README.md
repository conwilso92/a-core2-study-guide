# CompTIA A+ Core 2 220-1202 Study Guide

A comprehensive study guide for the CompTIA A+ Core 2 (220-1202) certification exam, synthesized from course materials and official exam objectives. Built as a single dark-mode HTML file with full anchor navigation.

🔗 **[View the Study Guide](https://conwilso92.github.io/aplus-core2-study-guide)**

---

## Coverage

All 12 modules mapped to the 4 official exam domains:

| Domain | Weight | Modules |
|---|---|---|
| Operating Systems | 31% | Mod. 11, 12, 13, 14, 15, 16, 17 |
| Security | 25% | Mod. 15, 18, 19, 20 |
| Software Troubleshooting | 22% | Mod. 14, 17, 19, 20 |
| Operational Procedures | 22% | Mod. 11, 21, 22 |

### What's Inside

- **Module 11 — Managing Support Procedures:** Documentation hierarchy (Policy/SOP/Guidelines/Knowledge Base/AAR), SLA uptime calculations (99.99% = 52 min/yr), ticketing system lifecycle, escalation tiers (0–3), professional communication best practices, OS types and file systems (Windows/macOS/Linux/Chrome OS/iOS/Android), end-of-life lifecycle implications
- **Module 12 — Configuring Windows:** Windows Settings vs Control Panel, key settings areas (Accounts, Privacy, Time, Ease of Access, Update & Security, Power), File Explorer and indexing options, key folder locations, administrative tool shortcuts (.msc and .exe reference), application installation (system requirements, OS compatibility, distribution methods, digital signatures, WSL), cloud-based applications (email, storage, collaboration, identity synchronization, licensing)
- **Module 13 — Managing Windows:** Management consoles (Local Users and Groups, Disk Management, Device Manager, Group Policy Editor, Certificate Manager, Task Scheduler), complete command-line tool reference (dir, cd, copy, robocopy, md/rd, diskpart, format, chkdsk, sfc, shutdown, net user, gpupdate, gpresult, regsvr32), Windows networking configuration (adapter settings, network profiles, UNC paths, VPN, WWAN, proxy, Windows Defender Firewall)
- **Module 14 — Supporting Windows:** Network troubleshooting commands (ipconfig /all, release/renew/flushdns, ping sequential test, tracert, nslookup, netstat), remote access technologies (RDP, Remote Assistance, WinRM, SSH, VNC, RMM), performance and troubleshooting tools (Task Manager, Event Viewer, Resource Monitor, Performance Monitor, msconfig), Windows boot process, boot recovery tools (Safe Mode, WinRE, System Restore, driver rollback, Reset this PC), common troubleshooting (BSOD, slow boot/performance, application crashing, services not starting, time drift)
- **Module 15 — Securing Windows:** Logical security concepts (CIA Triad, least privilege, implicit deny, ACLs, UAC, PAM), Windows authentication (username/password, Windows Hello — PIN/fingerprint/facial, MFA, TOTP, HOTP, SAML SSO), Active Directory and Group Policy (DCs, member servers, OUs, security groups, GPOs — LSDOU order, login scripts), NTFS vs share permissions (effective permissions, explicit deny, inheritance), home folders, roaming profiles, and folder redirection
- **Module 16 — Installing Operating Systems:** Windows editions comparison (Home/Pro/Enterprise/Education with feature and RAM limits), 32-bit vs 64-bit distinctions, N editions, installation types (clean install, in-place upgrade, unattended/answer file, PXE/network-based, multiboot, repair install), Windows 11 hardware requirements (TPM 2.0, UEFI + Secure Boot, supported CPU), MBR vs GPT partition styles
- **Module 17 — Supporting Other Operating Systems:** Linux command line (ls, cd, pwd, cp, mv, rm, mkdir, df, du, cat, grep, find, mount, cron), file permissions (chmod/chown, symbolic and numeric/octal modes — Read=4/Write=2/Execute=1), user management (sudo, su, user/group commands), package management (APT for Debian/Ubuntu, DNF for RHEL/Fedora), network and process commands (ping, traceroute, dig, curl, ps, top, kill), macOS interface (Dock, Menu bar, Spotlight, Mission Control, Terminal/Zsh), system folders (/System, /Library, ~/Library), Time Machine, FileVault, iCloud, Gatekeeper, app installation
- **Module 18 — Configuring SOHO Network Security:** Social engineering attacks (phishing, spear phishing, whaling, vishing, smishing, quishing, evil twin), SQL injection and XSS prevention, wireless security protocols (WEP/WPA2-PSK/WPA3-SAE comparison table), enterprise authentication (802.1X — supplicant/authenticator/auth server, EAP-TLS, PEAP, RADIUS, TACACS+, Kerberos), SOHO router security (default credentials, firmware updates, inbound/outbound/content filtering, port forwarding, UPnP risks, screened subnet/DMZ, Wi-Fi best practices), physical security controls (cable locks, biometric locks, smart card badges, mantrap, RFID tags, cameras)
- **Module 19 — Managing Security Settings:** Account hardening (password best practices per NIST, disable default admin/guest, lockout policy, least privilege), workstation security tools (Windows Defender AV, Windows Defender Firewall via wf.msc, EFS vs BitLocker comparison, AutoRun/AutoPlay risks, AppLocker), browser security (trusted sources, extensions, HTTPS/TLS certificates, private browsing, cache clearing, hardening), malware removal 7-step process (quarantine → disable System Restore → Safe Mode scan → remediate → re-enable restore → educate), common malware symptoms
- **Module 20 — Supporting Mobile Software:** Mobile OS security (screen lock, data protection encryption on iOS/Android, biometrics, MFA/TOTP, remote wipe, locator apps), MDM capabilities and Microsoft Intune, deployment models (BYOD/COPE/COBO/CYOD comparison table), mobile security threats (rooting, jailbreaking, sideloading, malware symptoms, location/geotag privacy), mobile troubleshooting (reboot, Safe Mode Android, app issues, failed OS update, connectivity, factory reset)
- **Module 21 — Using Data Security:** Backup types (full/incremental/differential with archive bit and speed comparison), 3-2-1 backup rule, GFS rotation scheme (Son/Father/Grandfather), Windows backup tools (File History, Backup and Restore), data classification and regulated data (PII, PHI, PCI, FERPA), prohibited content and licensing compliance (DRM, NDA, open-source permissive vs copyleft), data destruction methods (erasing/wiping, low-level format, degaussing, physical destruction, sanitization, e-waste), digital forensics and order of volatility, AI basics (NLP/ML/CV), AI limitations (bias/hallucinations/accuracy), public vs private AI, AI policy and AUP
- **Module 22 — Implementing Operational Procedures:** Change management 7-step process (RFC → risk analysis → CAB review → schedule → implement → rollback plan → end-user acceptance), asset management and lifecycle, software licensing tracking, warranty and service plan tiers, electrical safety (disconnect before work, CO₂ extinguishers, ESD mitigation with wrist straps), UPS sizing (VA = Wattage × 1.67), power issues (surge/brownout/blackout with mitigations), hazardous materials handling (MSDS/SDS), toner/battery/e-waste disposal, environmental controls (temperature, humidity, dust cleanup), safety procedures (lifting, trip hazards, PPE), scripting languages (Bash, PowerShell, Batch, VBScript, Python, JavaScript — extensions and syntax), core script constructs (variables, comments, shebang, control flow, operators), scripting best practices

---

## Related Study Tools

Part of a broader CompTIA certification study toolkit:

| Repo | Description |
|---|---|
| [CompTia-core1-flashcards](https://github.com/conwilso92/CompTia-core1-flashcards) | A+ Core 1 interactive flashcard app |
| [CompTia-core2-flashcards](https://github.com/conwilso92/CompTia-core2-flashcards) | A+ Core 2 interactive flashcard app |
| [network-plus-flashcards](https://github.com/conwilso92/network-plus-flashcards) | Network+ interactive flashcard app |
| [network-plus-study-guide](https://github.com/conwilso92/network-plus-study-guide) | Network+ N10-009 comprehensive study guide |
| [server-plus-study-guide](https://github.com/conwilso92/server-plus-study-guide) | Server+ SK0-005 comprehensive study guide |
| [security-plus-study-guide](https://github.com/conwilso92/security-plus-study-guide) | Security+ SY0-701 comprehensive study guide |
| [homelab](https://github.com/conwilso92/homelab) | Homelab documentation and configs |

---

## About

Built while studying for the CompTIA A+ certification at Star V Learning Centers, Jacksonville, FL. Materials synthesized from course slide decks and official 220-1202 exam objectives.

