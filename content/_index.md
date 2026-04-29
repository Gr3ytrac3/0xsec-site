---
date: '2025-05-29T10:00:00-04:00'
draft: false
title: 'Welcome to my domain'
description: 'Offensive security researcher, kernel security engineer, and low-level exploit developer. Operating at the boundary where software meets silicon.'
---

> *I find what should not be found.*

Most sites in this space hand you a wall of jargon that you're not used to, or clearly have no idea about. This one is different and among the few that actually give you valuable insight, knowing that not everyone can related with the content. I built it for the curious not just the credentialed. Whether you are into low-level systems, the kernel or just beginning to ask real questions or just trying to find your way, you belong here and you're welcome.


## What i share here

> I am not here to prove I am the smartest person in the room. I am here to make the room bigger.

There are so many things I will be sharing here but the below categories are likely the ones you will see

- **Technical**: here you have CVE analysis, kernel exploitation, low-level research, written in a way the reasoning is visible, not just the result. Because when the process is understood, the results become evident
- **Educational**: Concepts explained from first principles. I try my best to break them down to the lowest level possible and i avoid assumming that you know it. I'll often add a reference link to a more detailed source to avoid too much long writeups.
- **Personal Thoughts**: Basically The cost of craft. What it feels like to build something real. This the part most people often don't posts about.
- **Open**: Meaning that everything I build is shared. Every insight is documented. There's no benefit in hidden knowledge. It's a waste.

---

## Why Offensive Security Research, why Kernel security, why low-level

I didn't choose offensive security research, it chose me by process of elimination. Every time I tried to stay at the surface, something pulled me deeper.

It started with curiosity about how systems actually work, not how documentation says they work. I kept noticing the gap between the two. A function behaves one way in the manual and another way under pressure. A boundary that's supposed to hold doesn't. That gap is where offensive security lives, and I found I couldn't stop looking into it.

Kernel security became the natural anchor point. The kernel is where every abstraction eventually collapses into something real, memory, permissions, scheduling, hardware access. When I started working with Linux internals, tracing syscalls, reading /proc, writing kernel modules, I realized I wasn't just learning a subsystem, I was learning the ground truth that everything else is built on top of. Understanding attacks at that level means understanding attacks at every level, because the kernel is the final arbiter of what is and isn't permitted. That felt like the right place to invest.

The low-level orientation follows from the same logic. I've done web penetration testing. I've written detection scripts. But high-level work has a ceiling that's set by someone else's abstractions. When you work in C, in Assembly, when you're reading kernel source or analyzing a compiled binary without symbols, the ceiling disappears. You're reasoning directly about what the machine is doing. That kind of understanding doesn't become obsolete when a framework changes.

The covert channel research I published, where two binaries communicated exclusively through Unix file permission bits, came directly from that orientation. Nobody handed me that attack surface. I found it by thinking at a level where file permissions aren't just an access control mechanism but a writable state observable by any process with the right vantage point. That's what low-level thinking gives you: the ability to see attack surface that simply isn't visible from above.

I'm pursuing offensive security research because I want to produce knowledge that advances how the field understands real threats, not just find bugs, but explain why they exist, how they can be chained, and what they reveal about the assumptions baked into the systems we trust. Kernel security is the domain where that work is hardest, most consequential, and most needed.

---


## Contact

For vulnerability disclosures, research collaborations, or consulting engagements — see the [contact page](/0xsec-site/contact). PGP available on request.
