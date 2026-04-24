---
date: '2025-05-29T10:00:00-04:00'
draft: false
title: 'Welcome to my domaine'
description: 'Offensive security researcher, kernel security engineer, and low-level exploit developer. Operating at the boundary where software meets silicon.'
---

> *"I find what should not be found."*

I'm **Gr3ytrac3** — offensive security researcher and kernel engineer operating under [The OffSec Desk](https://github.com/Gr3ytrac3). My work lives at ring 0: vulnerability discovery, kernel exploitation, reverse engineering, and responsible disclosure.

<!--more-->

## What I Do

I research the Linux kernel attack surface — heap primitives, privilege boundaries, covert channels, and the subsystems nobody reads twice. When I find something, I document it fully and disclose it responsibly.

Current focus areas:

- **Kernel exploitation** — SLUB/SLAB heap spray, UAF primitives, KASLR bypass, SMEP/SMAP defeat
- **Vulnerability discovery** — attack surface mapping, IPC fuzzing, CVE-track responsible disclosure
- **Reverse engineering** — ELF static analysis, ROP chain construction, DWARF debug parsing
- **eBPF instrumentation** — tracepoint-based syscall interception, minimal-footprint kernel telemetry
- **Covert channels** — virtualization boundary crossing, side-channel identification
- **Post-exploitation** — audio attack surfaces, privilege escalation via multimedia subsystems

---

## Active Research

### QEMU/KVM → Host Audio Boundary Crossing
> `CWE-669 · CWE-284 · CWE-346` — CVSS estimated **6.5–8.0** — *Responsible disclosure in progress*

VM audio silently captured from host via `pw-record`. 440Hz sine tone injected into VM microphone input, confirmed via spectrogram analysis. Full attack surface documented across PipeWire/SPICE. Disclosure package submitted to virt-manager/libvirt and SPICE/PipeWire maintainers.

### Ring Buffer
Kernel-level logging framework for persistent event capture. Built in C for Linux x86_64 with minimal detection footprint.

### Enhanced Process Monitor
eBPF-based process telemetry with syscall-level visibility. Designed as a research instrument for exploit development workflows.

### The Invisible Wire
A file-permission-bit covert channel operating across KVM virtualization boundaries. Documented as a full research article with a C-based guest/host experiment.

### Talon OS
Custom OSINT-focused Linux distribution built for offensive intelligence operations.

---

## Language Stack

`C` · `x86_64 ASM` · `ARM64 ASM` · `eBPF` · `C++` · `Rust` · `Python` · `Bash`

---

## Writing

Research notes, exploit walkthroughs, and technical essays published on the [blog](/posts) and [Substack](https://substack.com/@cyberdevhq).

Recent topics: Linux audio attack surfaces · kernel syscall interception · black-box penetration testing · covert channel research · human purpose in the AI age.

---

## Contact

For vulnerability disclosures, research collaborations, or consulting engagements — see the [contact page](/contact). PGP available on request.

[@thecyberdevhq](https://x.com/thecyberdevhq) · [GitHub](https://github.com/Gr3ytrac3) · [cyberdev@proton.me](mailto:cyberdev@proton.me)
