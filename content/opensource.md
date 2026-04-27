---
date: '2025-05-29T10:00:00-04:00'
draft: false
title: 'Things I built and worked on'
description: 'Tools, exploits, and research released to the public domain.'
---


> The best way to learn how things break is to build the tools that break them.

I believe in open research. Everything here is released for educational purposes — for the security community, kernel engineers, and anyone curious enough to read the source.

---

## Tools & Projects

### *- KERNEX* </span> <span style="color: #a0f600;">(Ongoing)</span>

<span style="color: orange;">Python - FAISS - Claude API - Kernel Security - RAG 

A reasoning engine that helps security researchers understand whether a kernel bug is exploitable, why it is, and how to approach it. Built on a curated knowledge base of real exploitation patterns. Not a scanner. Not a magic button. A thinking partner.


### *- RINGBUFFER* </span> <span style="color: #a0f600;">(Live)</span>

<span style="color: orange;">Python - PySide6 - Async - Kernel</span>

A Python/PySide6 tool for real-time kernel log analysis with async event-driven architecture. Built for researchers who need to watch the kernel's internal state without leaving their workflow. Direct /dev/kmsg streaming.

Check [here](https://github.com/The-OffSec-Desk/ringbuffer)



### *- ELPM* </span> <span style="color: #a0f600;">(Live)</span> 
<span style="color: orange;">Python - PyQt6- Linux - Process Monitoring</span>

A PyQt6-based Linux process monitoring tool with a focus on security-relevant process behavior. Built to understand what the kernel sees when processes run — not just what they show you.

Check [here](https://github.com/The-OffSec-Desk/enhanced-process-monitor)

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
