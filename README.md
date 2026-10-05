# Awesome-Desktop-Operating-System-Legacy

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.

Here is the complete, ready-to-paste README.md for **Awesome-Desktop-Operating-System-Legacy**.

---

# Awesome-Desktop-Operating-System-Legacy

**Curated List of Legacy Operating Systems & Open-Source Alternatives**
*Focused on Emulation, Preservation & Modern Reimplementations of Classic Desktop OS*
**Last updated: October 2026**

This repository tracks notable **legacy desktop operating systems** and **open-source alternatives** that keep them alive. These tools help retro computing enthusiasts, historians, and developers run, preserve, and reimagine the classic desktop experiences that shaped modern computing.

**Examples** include Windows 95, Windows 98, Windows 3.1, Mac OS 8, Mac OS 9, OS/2 Warp, AmigaOS, BeOS, NeXTSTEP, and MS-DOS (the legacy category leaders).

**Open-source emphasis**: The open-source ecosystem for legacy OS is **exceptionally vibrant and production-proven**. **86Box** is the premier low-level x86 emulator for running MS-DOS, older Windows, OS/2, and BeOS with unprecedented hardware accuracy . **v86** runs Windows 95/98 and MS-DOS directly in your browser via WebAssembly . **SerenityOS** is a from-scratch modern OS that recreates the aesthetic of late-1990s productivity software . **Previous** brings NeXTSTEP back to life with JIT compilation . **FreeDOS** provides a fully open-source MS-DOS replacement . This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [💾 Legacy Operating Systems](#-legacy-operating-systems)
- [🔓 Open-Source Alternatives & Emulators](#-open-source-alternatives--emulators)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 💾 Legacy Operating Systems

> **📊 Market Context**: The legacy OS preservation market is **not commercial** — these operating systems are **abandoned, unsupported, and largely unavailable for purchase**. The value lies in **historical preservation, retro gaming, and software archaeology**. Emulation has become the primary path to running these systems, with modern hardware lacking the drivers and compatibility layers needed for native execution. The ecosystem is **highly fragmented** — each legacy OS has its own dedicated emulator, community, and preservation challenges. No single tool dominates; enthusiasts typically run multiple emulators for different systems.

| Operating System | Description | Release Era | Current Status | Preservation Path |
|-----------------|-------------|-------------|----------------|-------------------|
| **[Windows 95](https://en.wikipedia.org/wiki/Windows_95)** | **The OS that brought the Start menu and taskbar to the masses.** 32-bit preemptive multitasking, Plug and Play, long filenames. | **1995** | **Discontinued** — Microsoft ended support December 31, 2001. | **86Box** (hardware-accurate emulation) , **v86** (browser-based) , **DOS Wasm X** (browser-based with Windows 95 installation support) . |
| **[Windows 98](https://en.wikipedia.org/wiki/Windows_98)** | **The refined consumer Windows.** USB support, FAT32, Internet Explorer integration, and the first Windows to include Windows Update. | **1998** | **Discontinued** — Microsoft ended support July 11, 2006. | **86Box** (recommended for accuracy) , **v86** (browser-based, playable games included) . |
| **[Windows 3.1](https://en.wikipedia.org/wiki/Windows_3.1)** | **The first widely successful Windows.** 16-bit graphical environment running on top of MS-DOS. Program Manager, File Manager, and the iconic Solitaire. | **1992** | **Discontinued** — Microsoft ended support December 31, 2001. | **86Box** (low-level emulation from 8086 up) , **DOSBox-X** and derivatives. |
| **[Mac OS 8](https://en.wikipedia.org/wiki/Mac_OS_8)** | **Apple's mature 68k Mac OS.** Multi-threaded Finder, platinum appearance, Sherlock, and improved performance. | **1997** | **Discontinued** — superseded by Mac OS 9, then OS X. | **Basilisk II** (68k Mac emulator, supports up to Mac OS 8.1) , **Mini vMac** . |
| **[Mac OS 9](https://en.wikipedia.org/wiki/Mac_OS_9)** | **The final classic Mac OS.** Carbon API, Sherlock 2, multiple users, and the last Apple OS before OS X. | **1999** | **Discontinued** — Apple ended support in 2002. | **SheepShaver** (PowerPC Mac emulator, runs OS 9) , **QEMU** (with mac99 machine) . |
| **[OS/2 Warp](https://en.wikipedia.org/wiki/OS/2)** | **IBM's ambitious multitasking OS.** Preemptive multitasking, HPFS, and the Workplace Shell object-oriented desktop. | **1994** | **Discontinued** — IBM ended support December 31, 2006. | **86Box** (supports OS/2) , **Virtual PC 2004** (legacy VM option) , **ArcaOS** (modern commercial continuation) . |
| **[AmigaOS](https://en.wikipedia.org/wiki/AmigaOS)** | **The multimedia powerhouse of the 80s and 90s.** Preemptive multitasking, custom chips for graphics and sound, and the Workbench desktop. | **1985** | **Still developed** — AmigaOS 4.x and MorphOS continue on PowerPC. | **WinUAE** (most complete Amiga emulator) , **FS-UAE** (simplified configuration) . |
| **[BeOS](https://en.wikipedia.org/wiki/BeOS)** | **The media-optimized OS that almost changed computing.** 64-bit journaling filesystem, pervasive multithreading, and the BeBox hardware. | **1995** | **Discontinued** — Be Inc. sold assets to Palm in 2001. | **VirtualBox** (BeOS 5.0.3 runs in VM) , **86Box** (supports BeOS) . |
| **[NeXTSTEP](https://en.wikipedia.org/wiki/NeXTSTEP)** | **The OS that became macOS.** Objective-C, Display PostScript, Interface Builder, and the foundation for Apple's modern operating systems. | **1988** | **Discontinued** — NeXT merged into Apple in 1997. | **Previous** (JIT-accelerated 68k emulator) , **VMware** (NeXTSTEP 3.3 x86 in VM) . |
| **[MS-DOS](https://en.wikipedia.org/wiki/MS-DOS)** | **The foundation of PC computing.** Command-line interface, FAT filesystem, and the platform that launched a thousand games. | **1981** | **Discontinued** — Microsoft ended support in 2001. | **FreeDOS** (fully open-source MS-DOS replacement) , **DOSBox** (game-focused emulation), **DOS Wasm X** (browser-based) . |

## 🔓 Open-Source Alternatives & Emulators

Sorted by relevance to legacy OS preservation. Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|------|-------------|-------|
| **[86Box](https://github.com/86Box/86Box)** — **The premier low-level x86 emulator for legacy OS.** Emulates 8086 through Mendocino-era Celeron with **focus on hardware accuracy**. Supports **MS-DOS, older Windows, OS/2, BeOS, NeXTSTEP, and many Linux distributions** . Wide range of emulated systems from IBM PC 5150 (1981) to PCI-era machines. Video adapters, sound cards, network adapters, and SCSI controllers all emulated. **GPL-2.0**. | [![Stars](https://img.shields.io/github/stars/86Box/86Box?style=social&color=white)](https://github.com/86Box/86Box/stargazers) | ~3,500 |
| **[v86](https://github.com/copy/v86)** — **x86 virtualization in your browser, powered by WebAssembly.** Runs **Windows 95, 98, MS-DOS, and various Linux distributions** directly in any modern browser. Emulates x86 CPU, VGA, NE2000, SoundBlaster 16. Embeddable via JavaScript API. **BSD-2-Clause**.  | [![Stars](https://img.shields.io/github/stars/copy/v86?style=social&color=white)](https://github.com/copy/v86/stargazers) | ~22,000 |
| **[FreeDOS](https://github.com/FDOS/kernel)** — **The fully open-source MS-DOS replacement.** Runs classic DOS games and business software. Actively developed with kernel, utilities, and package ecosystem. **GPL-2.0**.  | [![Stars](https://img.shields.io/github/stars/FDOS/kernel?style=social&color=white)](https://github.com/FDOS/kernel/stargazers) | ~2,000 |
| **[DOS Wasm X](https://github.com/nbarkhina/DosWasmX)** — **Browser-based DOS/Windows emulator based on DOSBox-X.** Supports **Windows 95 and Windows 98 installation** via drag-and-drop of your own ISO. Hard disk saves directly to browser storage. Docker deployment available.  | [![Stars](https://img.shields.io/github/stars/nbarkhina/DosWasmX?style=social&color=white)](https://github.com/nbarkhina/DosWasmX/stargazers) | ~500 |
| **[Previous](https://github.com/rcarmo/previous-jit)** — **NeXTSTEP emulator with modern JIT compilation.** Emulates **68030/68040 CPUs with integrated MMU** (all NeXT computers used these). Near-complete FPU emulation. JIT fork enables booting NeXTSTEP with improved performance . | [![Stars](https://img.shields.io/github/stars/rcarmo/previous-jit?style=social&color=white)](https://github.com/rcarmo/previous-jit/stargazers) | ~100 |
| **[SerenityOS](https://github.com/SerenityOS/serenity)** — **A love letter to '90s user interfaces.** Modern 64-bit OS written from scratch with **glass-and-Aqua graphical interface inspired by early 2000s**, preemptive multitasking, TCP/IP stack, browser with JavaScript, and **300+ ports of open-source software**. **BSD-2-Clause**.  | [![Stars](https://img.shields.io/github/stars/SerenityOS/serenity?style=social&color=white)](https://github.com/SerenityOS/serenity/stargazers) | ~35,000 |
| **[ArcaOS](https://www.arcanoae.com/)** — **Modern commercial continuation of OS/2.** Runs **all OS/2 Warp 4 applications natively**. Supports running as guest OS in VirtualBox, VMware, and VirtualPC. Requires 64-bit CPU and 512MB RAM. **Commercial**.  | [![ArcaOS](https://img.shields.io/badge/ArcaOS-Commercial-blue)](https://www.arcanoae.com/) | N/A |
| **[III-Millennium OS](https://github.com/511break-AS/III-Millennium-OS)** — **Experimental 32-bit OS written from scratch in C and Assembly.** Custom window manager with **glass-and-Aqua interface inspired by early 2000s**, preemptive multitasking, Ext2 filesystem, TCP/IP stack, and **local AI assistant** with physical permission (drag the robot mascot to grant access). **Alpha**.  | [![Stars](https://img.shields.io/github/stars/511break-AS/III-Millennium-OS?style=social&color=white)](https://github.com/511break-AS/III-Millennium-OS/stargazers) | ~100 |
| **[DosWasmX](https://github.com/nbarkhina/DosWasmX)** — See DOS Wasm X above. | — | — |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[Basilisk II](https://github.com/kanjitalk755/macemu)** — 68k Mac emulator supporting Mac OS up to 8.1 . |
| **[SheepShaver](https://github.com/kanjitalk755/macemu)** — PowerPC Mac emulator running Mac OS 9 . |
| **[WinUAE](https://github.com/tonioni/WinUAE)** — Most complete Amiga emulator with JIT and RTG support . |
| **[FS-UAE](https://github.com/FrodeSolheim/fs-uae)** — Simplified Amiga emulator for easier configuration . |
| **[Mini vMac](https://github.com/zydeco/minivmac4raden)** — Compact 68k Mac emulator . |
| **[QEMU](https://github.com/qemu/QEMU)** — General-purpose emulator supporting Mac OS 9 via mac99 machine . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's a legacy OS or open-source alternative.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Legacy operating systems are abandoned and unsupported.** They contain **unpatched security vulnerabilities** and should **never be connected to the internet** or used for sensitive data. Run them in isolated emulators or VMs only.
- **Legal caveat**: Installing legacy operating systems requires **your own legitimate copies** of the original installation media and licenses. This repository does not host or distribute copyrighted OS images.
- **Open-source reality**: The open-source ecosystem for legacy OS preservation is **exceptionally vibrant and production-proven**. **86Box** provides hardware-accurate emulation for MS-DOS, Windows, OS/2, and BeOS . **v86** and **DOS Wasm X** run Windows 95/98 directly in the browser . **FreeDOS** offers a fully open-source MS-DOS replacement . **SerenityOS** demonstrates that building a modern OS inspired by classic interfaces is not only possible but produces a **35,000-star community** . **Previous** brings NeXTSTEP back with JIT compilation . The open-source path is **universally viable** for retro computing enthusiasts.

---

**Made for retro computing enthusiasts, software preservationists, emulation developers, and digital archaeologists.**
Let's preserve the history of desktop computing while building its future.
