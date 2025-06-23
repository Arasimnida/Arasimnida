# 🧑‍🔬☣️ whoami 🧪

Hi. I build Windows malware in Rust just to understand how these things work.  
How code becomes presence, how persistence is earned, and how a program becomes something more than just a file and become a nightmare.

They're not just binaries. They're creatures.  
They adapt, persist, and sometimes outsmart the system.

Rust is the tool. Curiosity is the motive.  
I like the moment when it starts to act like it's alive.

> **⚠️ WARNING**
>   This code is provided for educational and research purposes only.  
>   You are solely responsible for how you use it.  
>   Test everything in isolated, controlled environments. Never deploy outside lab conditions.
>
> **Malware is illegal and for nerds.**

---
## 🛠 Projects I’m exploring ¯\\_(ツ)_/¯

#### [`Reflective PE loader`](https://github.com/Arasimnida/reflective-pe-loader)

Manual in-memory PE loading in Rust. No touching disk, no LoadLibrary.  
Implements relocations, imports, TLS, memory protections, and DllMain execution.

> Goal: Digital BSL-4.

#### [`Process injection techniques`](https://github.com/Arasimnida/windows-process-injection)

Non-exhaustive collection of classic and modern DLL/shellcode injection methods.  
Everything modular and runnable from the CLI.

> Goal: Understand how Windows injectors work.

#### [`antilysis`](https://github.com/percept-denigrate/antilysis)

Rust crate developed with a friend for detecting analysis environments:
- Tooling presence, MAC patterns, sandbox artifacts, user interaction checks  
- Inspired by academic papers and real-world malware

> Goal: Explore dynamic analysis evasion.

---

## 🧬 Home-Made Specimens 🦠

#### [`Basic Windows backdoor`](https://github.com/Arasimnida/Windows-Backdoor) – Digital BSL-3

Simple remote access tool (RAT) using DLL injection and port knocking.  
Listens silently until a custom UDP sequence is received, then opens a TCP shell for remote command execution.

> Built to explore stealth activation, persistence, and remote control under user context.

#### [`Basic infostealer/spyware`](https://github.com/percept-denigrate/windows-malware) – Digital BSL-3

Lightweight infostealer with persistence, keylogging, and screenshot capabilities.  
Grabs credentials from Chromium-based browsers and exfiltrates via Discord webhooks.

> Not advanced, but useful for practicing payload chaining and basic C2 design.

---

## 📚 Resources I like

- [Microsoft Win32 API reference](https://learn.microsoft.com/en-us/windows/win32/api/)
- [Rust bindings for Windows](https://microsoft.github.io/windows-docs-rs/doc/windows/Win32/)
- [vx-underground](https://vx-underground.org/)
- Malware papers & conference talks (DEFCON, BlackHat, OffensiveCon...)
- GitHub repos by unknown geniuses
- The Internet
