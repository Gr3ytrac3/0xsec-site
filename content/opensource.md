---
date: '2025-05-29T10:00:00-04:00'
draft: false
title: 'Open Source'
description: 'Tools, exploits, and research released to the public domain.'
---

> *"The best way to learn how things break is to build the tools that break them."*

I believe in open research. Everything here is released for educational purposes — for the security community, kernel engineers, and anyone curious enough to read the source.

---

## Tools & Projects

### 🔧 [project-name] — *Kernel Syscall Tracer*
> Language: `C` · Platform: `Linux x86_64` · Status: `Active`

A low-level syscall interception framework built on top of eBPF and raw tracepoints. Designed for tracing kernel behaviour during exploit development without triggering common detection mechanisms.

- Minimal footprint — no kernel module required
- Supports real-time filtering by PID, UID, or syscall number
- Outputs structured JSON for pipeline integration

```bash
git clone https://gitlab.com/yourcyberdev/project-name
```

---

### 🔧 [project-name] — *ELF Binary Analyser*
> Language: `Python` · Platform: `Linux` · Status: `Active`

A static analysis tool for ELF binaries focused on identifying exploitable patterns — format string vulnerabilities, use-after-free candidates, and unsafe function usage — without running the binary.

- Parses DWARF debug info for precise source mapping
- Identifies ROP gadget chains automatically
- Integrates with GDB and pwndbg workflows

```bash
git clone https://gitlab.com/yourcyberdev/project-name
```

---

### 🔧 [project-name] — *PipeWire Attack Surface Mapper*
> Language: `C / Shell` · Platform: `Linux` · Status: `Research`

Born from personal research into the Linux audio stack. Maps the PipeWire IPC attack surface, enumerates exposed sockets, and tests for permission misconfigurations that could allow privilege escalation through multimedia subsystems.

- Documents undocumented PipeWire internal APIs
- Fuzzes graph node connections for unexpected state transitions
- Includes a working PoC for socket permission bypass (patched)

```bash
git clone https://gitlab.com/yourcyberdev/project-name
```

---

## Research & Write-ups

Alongside tools, I release structured research notes and proof-of-concept write-ups on vulnerabilities I've analysed. These are not weaponised exploits — they are documented for understanding and defence.

| Write-up | Topic | CVE |
|---|---|---|
| Linux Audio Stack Attack Surface | PipeWire / ALSA | N/A |
| Kernel Syscall Interception Techniques | eBPF / tracepoints | N/A |
| *More coming* | — | — |

---

## Philosophy

I don't release tools to cause harm. I release them because the best defenders are people who understand offense deeply. Every tool here started as a question I couldn't answer with existing software.

If you find a bug, want to contribute, or want to discuss the research — reach out.

---

## Repositories

- **GitLab** → [gitlab.com/yourcyberdev](https://gitlab.com/example)
- **BitBucket** → [bitbucket.org/yourcyberdev](https://bitbucket.org/example)-
