# eJPT Vault (Offline Reference Site)

A fully self-contained, offline-ready study vault for the eLearnSecurity Junior Penetration Tester v2 (eJPTv2) exam. Built from real course notes across the full INE curriculum, TryHackMe rooms, Zero to Hero walkthroughs, and community cheat sheets.

---

## Usage

Download [index.html](index.html) and open it in any browser — no internet connection, server, or installation required. Works from a USB drive on any OS.

This project is also hosted online at https://IP-Medjed.github.io/EJPT-Vault/

### Search

Type any keyword into the search bar to filter across all entries instantly — commands, tool names, CVEs, concepts, techniques, or room names all work.

> Examples: `hydra`, `meterpreter`, `ms17-010`, `cron`, `XSS`, `pivoting`, `suid`, `smb`, `sqlmap`, `eternalblue`, `kiwi`

Press **Ctrl+K** to focus the search bar. Press **Esc** to clear the search and return to browsing.

### Category navigation

Click any category in the sidebar to expand or collapse it. Click a note title to load it in the main panel. All 1,492 internal cross-links between notes are clickable.

---

## Contents

| Category | Count | Contents |
| --- | --- | --- |
| **Dashboard** | 3 | Home, INE Lab Index, Wordlist Quick Reference |
| **Domain Notes** | 4 | Methodology Overview, Exam Checklist, Lab Index, Study Guide MOC |
| **Zero to Hero** | 6 | Full exam simulation series — Metasploit/EternalBlue, Windows SMB/PrintSpoofer, SQLi/SQLMap, Linux PrivEsc, Exam Simulation |
| **SlabFile** | 4 | Domain study guides — Assessment Methodologies, Host & Network Pentesting, Post-Exploitation, Web App Pentesting |
| **THM - Active Directory** | 7 | Full AD kill chain — Basics, Breaching, Enumerating, Exploiting, Lateral Movement, Persisting, Credentials Harvesting |
| **THM - Crypto & Hashing** | 3 | Encryption Crypto 101, Hashing Crypto 101, John the Ripper Basics |
| **THM - Exploitation CTFs** | 12 | Alfred, Basic Pentesting, Blue, Kenobi, Mr Robot, Pickle Rick, Relevant, Retro, Simple CTF, Skynet, Steel Mountain, Vulnversity |
| **THM - Fundamentals** | 2 | DNS Manipulation, Introductory Networking |
| **THM - Metasploit** | 3 | Introduction, Exploitation, Meterpreter |
| **THM - Privilege Escalation** | 4 | Common Linux PrivEsc, Linux PrivEsc Tib3rius, Linux Privilege Escalation, Windows Privilege Escalation |
| **THM - Scanning & Enumeration** | 3 | Nmap, Nmap Advanced, Nmap Live Host Discovery |
| **THM - Web Applications** | 4 | Web Fundamentals, OWASP Top 10, Content Discovery, SQL Injection |
| **THM - Other** | 2 | PowerShell for Pentesters, What the Shell |
| **INE Labs - Exploitation** | 35 | Windows & Linux exploitation labs covering SMB, FTP, SSH, HTTP, RDP, WinRM, WebDAV, Shellshock, and more |
| **INE Labs - Password Attacks** | 2 | Password cracking and credential harvesting labs |
| **INE Labs - Persistence & Pivoting** | 6 | Autoroute, port forwarding, proxychains, persistence mechanisms |
| **INE Labs - Post-Exploitation** | 8 | Meterpreter, Kiwi/Mimikatz, local exploit suggester, enumeration, clearing tracks |
| **INE Labs - Privilege Escalation** | 9 | SUID, sudo abuse, cron exploitation, unquoted service paths, kernel exploits, token impersonation |
| **INE Labs - Reconnaissance** | 4 | Passive and active reconnaissance techniques |
| **INE Labs - Scanning & Enumeration** | 25 | Nmap, SMB, FTP, SSH, HTTP, MySQL, SMTP enumeration labs |
| **INE Labs - Shells & File Transfer** | 8 | Reverse shells, bind shells, msfvenom payloads, file transfer methods |
| **INE Labs - Tools & Frameworks** | 3 | Metasploit Framework, Burp Suite, other core tools |
| **INE CTFs** | 13 | Full CTF walkthroughs — Enumeration, Vulnerability Assessment, System/Host Based Attacks, Network-Based Attacks, Metasploit Framework |
| **Cheat Sheets** | 5 | Quick reference sheets for core tools and techniques |
| **Templates** | 2 | Note templates for consistent documentation |
| **Import Zone** | 1 | Staging area for incoming notes |
| **PayloadsAllTheThings** | 141 | Community payload reference — reverse shells, web shells, SQLi, XSS, file inclusion, command injection, and more |
| **Other** | 2 | Google Dorking, Nmap Cheatsheet |

**Total: 321 notes across 28 categories with 1,492 internal cross-links**

---

## Self-contained & portable

- Single `.html` file (~3.4 MB)
- Zero dependencies — no CDN, no external fonts loaded at runtime (Google Fonts import for JetBrains Mono and Source Sans 3 on first load only), no JavaScript libraries
- Custom cat logo embedded as base64 data URI
- Tested in Chrome, Firefox, Edge, and Safari on Windows, Linux, and macOS

---

## Disclaimer

This tool is intended for use in authorized penetration testing engagements and certification exam preparation only. Always ensure you have explicit written permission before testing any system.

---

## Credits

- Nmap Cheatsheet section sourced from [ekol-x9/nmap-cheatsheet](https://github.com/ekol-x9/nmap-cheatsheet)
- PayloadsAllTheThings section sourced from [swisskyrepo/PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
