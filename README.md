<!-- Header -->
<div align="center">

```
  ██████╗ ██╗   ██╗██╗   ██╗
 ██╔════╝ ██║   ██║╚██╗ ██╔╝
 ██║  ███╗██║   ██║ ╚████╔╝ 
 ██║   ██║██║   ██║  ╚██╔╝  
 ╚██████╔╝╚██████╔╝   ██║   
  ╚═════╝  ╚═════╝    ╚═╝   
```

**Systems & Security | C++ | Low-Level Internals**

[![Magshimim](https://img.shields.io/badge/Magshimim-Cyber_Program-blue?style=flat-square)](https://www.magshimim.cyber.org.il/)
[![Focus](https://img.shields.io/badge/Focus-Offensive_Security-red?style=flat-square)]()
[![Language](https://img.shields.io/badge/Primary_Lang-C%2B%2B-00599C?style=flat-square&logo=cplusplus)]()

</div>

---

## About

Cybersecurity student in Israel's **Magshimim** program, focused on systems programming and offensive security.  
I gravitate toward understanding things at the layer most people skip — memory layout, packet structure, syscall internals.  
Currently building toward a future in elite cyber defense.

---

## Projects

### 🛡️ ARP Spoofing Detection Tool — `C++`
Real-time MITM detection via raw packet capture. Maintains a MAC→IP trust map using `std::unordered_map`, flags ARP replies where the claimed IP doesn't match the expected mapping. Designed for live network monitoring with persistent MAC learning.

> `libpcap` · Raw sockets · Network forensics · `unordered_map`

---

### 📁 MyFS — `C++`
Custom flat filesystem built on a 1MB block device image. Designed the full on-disk layout from scratch: magic-byte header, fixed file table, data area. Debugged heap pointer serialization bugs by reading raw hexdumps.

> On-disk structures · Binary I/O · Memory layout · Filesystem design

---

### 🖼️ Gallery — `C++` + `SQLite` + `WinAPI`
Photo album manager with a full SQLite backend. Implemented `DatabaseAccess` with CRUD for users, albums, pictures, and tags. Integrated WinAPI to launch images in Paint via `CreateProcessA`, with `SetConsoleCtrlHandler` for clean Ctrl+C shutdown.

> `sqlite3` · `CreateProcessA` · WinAPI · Git/GitLab workflow

---

### 🐍 MITMSuite — `Python`
Modular command-dispatch network tool. Built prefix-matching for multi-word commands with argument extraction — designed as a clean framework for layering network attack/analysis modules.

> Python sockets · Command dispatch · Network tooling

---

### 🔐 AES Steganography Loader — `C++`
Builder + loader for covert payload delivery research. AES-256-CBC encryption via OpenSSL EVP, LSB steganography using `stb_image`/`stb_image_write`, with RW→RX memory permission transitions for in-memory execution.

> OpenSSL · Steganography · Memory permissions · Malware research

---

## Tech Stack

```
Languages   │ C++  ·  C  ·  Python  ·  x86 Assembly  ·  Bash
Systems     │ Linux internals  ·  Windows WinAPI  ·  Custom filesystems
Networking  │ Raw sockets  ·  ARP  ·  SMB  ·  libpcap  ·  Wireshark
Security    │ Privilege escalation  ·  AV evasion  ·  Password cracking
Tools       │ SQLite  ·  OpenSSL  ·  Nmap  ·  Metasploit  ·  John / Hydra
Concepts    │ Memory allocators  ·  Syscalls  ·  ETW  ·  SLUB/SLAB  ·  Heap internals
```

---

## Currently

- 📌 Polishing the ARP detection tool for portfolio
- 📌 Deepening offensive security fundamentals (TryHackMe + independent research)
- 📌 Building toward IDF's elite cyber units

---

<div align="center">

*"The goal isn't to write code that works. It's to write code that's impossible to misread."*

</div>
