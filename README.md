# eJPT Vault

Offline, self-contained reference site for eJPT exam prep and penetration testing study. 319 notes across 28 categories with deep content search, copyable commands, and full Obsidian callout support.

Built from real course notes across the full INE curriculum, TryHackMe rooms, Zero to Hero walkthroughs, and community cheat sheets.

---

## Usage

Browse the vault online at **https://IP-Medjed.github.io/EJPT-Vault/**

Or download `index.html` and open it in any browser — no internet connection, server, or installation required. Works from a USB drive on any OS.

### Search

Type any keyword into the search bar to filter across all notes instantly. Search matches note titles AND full note body content — commands, tool names, CVEs, concepts, techniques, flags, or room names all work.

> Examples: `hydra`, `meterpreter`, `ms17-010`, `cron`, `XSS`, `pivoting`, `suid`, `smb`, `sqlmap`, `eternalblue`, `kiwi`

Press **Ctrl+K** to focus the search bar. Press **Esc** to clear the search and return to browsing.

### Navigation

- Click the cat logo header to collapse/expand the sidebar
- Click any category to expand or collapse it
- Use **Collapse All / Expand All** to toggle all categories at once
- **Breadcrumbs** at the top of each note show your current location
- **Recently viewed** section tracks your last 5 visited notes (collapsible)
- **In-note table of contents** auto-generates for longer notes from h2/h3 headings
- **Back-to-top** button appears after scrolling in long notes
- All 1,492 internal cross-links between notes are clickable

### Code Blocks

Hover over any code block to reveal the **Copy** button. Click to copy the command to your clipboard.

---

## Features (v1.1)

- **Deep content search** with lazy indexing and debounced input
- **582 styled Obsidian callouts** — tip, warning, important, exam, info, danger, critical, check
- **623 blockquotes** properly rendered from Obsidian markdown
- **3,265 copyable code blocks** with one-click clipboard copy
- **Collapsible sidebar** with cat logo toggle and caret indicator
- **Breadcrumb navigation** showing Home / Category / Note path
- **Back-to-top button** for long notes
- **Collapse/Expand All** categories toggle
- **Recently viewed notes** with persistent collapse state
- **In-note table of contents** for notes with 3+ headings
- **Responsive layout** for half-screen and mobile viewports
- **External link** to PortableJPTv2 reference under Dashboard

---

## Contents

| Category | Count | Contents |
| --- | --- | --- |
| **Dashboard** | 4 | Home, INE Lab Index, Wordlist Quick Reference, PortableJPTv2 (external) |
| **Quick Reference** | 4 | Domain study guides — Assessment Methodologies, Host & Network Pentesting, Post-Exploitation, Web App Pentesting |
| **Domain Notes** | 4 | Methodology Overview, Exam Checklist, Lab Index, Study Guide MOC |
| **Zero to Hero** | 6 | Full exam simulation series — Metasploit/EternalBlue, Windows SMB/PrintSpoofer, SQLi/SQLMap, Linux PrivEsc, Exam Simulation |
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
| **Cheat Sheets** | 3 | eJPT Cheat Sheet (enriched), CheatSheets MOC, GTFOBins Quick Reference |
| **Templates** | 2 | Note templates for consistent documentation |
| **Import Zone** | 1 | Staging area for incoming notes |
| **PayloadsAllTheThings** | 141 | Community payload reference — reverse shells, web shells, SQLi, XSS, file inclusion, command injection, and more |
| **Other** | 2 | Google Dorking, Nmap Cheatsheet |

**Total: 319 notes across 28 categories with 1,492 internal cross-links**

---

## Self-contained & portable

- Single `.html` file (~3.5 MB)
- Zero dependencies — no CDN, no JavaScript libraries, no localStorage
- Google Fonts import (JetBrains Mono + Source Sans 3) on first load only
- Custom cat logo embedded as base64 data URI
- Tested in Chrome, Firefox, Edge, and Safari on Windows, Linux, and macOS

---

## Disclaimer

This tool is intended for use in authorized penetration testing engagements and certification exam preparation only. Always ensure you have explicit written permission before testing any system.

---

## Credits

- [ekol-x9/nmap-cheatsheet](https://github.com/ekol-x9/nmap-cheatsheet) — Nmap reference tables
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) — Community payload reference
- [OvergrownCarrot1](https://www.youtube.com/@OvergrownCarrot1) — Zero to Hero eJPT series
- Built with assistance from Claude (Anthropic)

## License

BSD 3-Clause — see [LICENSE](LICENSE)
