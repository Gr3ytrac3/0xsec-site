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

### *- KERNEX* </span> <span style="color: green;">(Ongoing)</span>

<span style="color: orange;">Python - FAISS - Claude API - Kernel Security - RAG 

A reasoning engine that helps security researchers understand whether a kernel bug is exploitable, why it is, and how to approach it. Built on a curated knowledge base of real exploitation patterns. Not a scanner. Not a magic button. A thinking partner.


### *- RINGBUFFER* </span> <span style="color: green;">(Live)</span>

<span style="color: orange;">Python - PySide6 - Async - Kernel</span>

A Python/PySide6 tool for real-time kernel log analysis with async event-driven architecture. Built for researchers who need to watch the kernel's internal state without leaving their workflow. Direct /dev/kmsg streaming.

Check [here](https://github.com/The-OffSec-Desk/ringbuffer)



### *- ELPM* </span> <span style="color: green;">(Live)</span> 
<span style="color: orange;">Python - PyQt6- Linux - Process Monitoring</span>

A PyQt6-based Linux process monitoring tool with a focus on security-relevant process behavior. Built to understand what the kernel sees when processes run — not just what they show you.

Check [here](https://github.com/The-OffSec-Desk/enhanced-process-monitor)

---

## Research & Write-ups

Alongside tools, I release structured research notes and proof-of-concept write-ups on vulnerabilities I've analysed. These are not weaponised exploits — they are documented for understanding and defence.

I as well take pleasure in solving challenges from crackmes.ones. Not all of them are mentioned here, so you can check them out on my page over <a href="https://crackmes.one/user/Cyberdev" style="color: orange;">here</a>

| Write-up | Category | Writeup | Date
|---|---|---|---|
Integer Overflow — From Reverse Engineering to Infinite Passwords | Crackmes | <a href="https://crackmes.one/crackme/6894d8e98fac2855fe6fb3ff" style="color: green;">Writeup</a> | 2026-03-06
Covert Channels — Intercepting a File Permission Chat Protocol | Crackmes | <a href="https://crackmes.one/crackme/68692019aadb6eeafb398fcf" style="color: green;">Writeup</a> | 2026-03-08
