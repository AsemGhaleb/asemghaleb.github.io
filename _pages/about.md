---
layout: about
title: about
permalink: /
subtitle: Senior Research Engineer at Huawei Technologies Canada, Vancouver &middot; PhD, <a href='https://www.ubc.ca'>UBC</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I work at the intersection of security research and software engineering, taking ideas from problem to production: framing the problem, designing the approach, building it, benchmarking it against the state of the art, and shipping it. At Huawei Technologies Canada, I research and build security detection technologies used in endpoint systems, network gateways, and cloud sandboxes.

**What I work on**

- **AI-agent security.** Detecting malicious AI-agent skills, a new malware channel where most of the malicious content sits in natural-language instruction files that code scanners cannot read. The engine combines static analysis with an LLM-based semantic judgment stage hardened against prompt injection.
- **Binary analysis and AI-based malware detection.** A binary analysis engine that turns PE and ELF executables into AI-model-ready features, with a custom disassembler and function discovery, used for AV scanning, code similarity, and LLM-assisted analysis.
- **CPU emulation and dynamic binary translation.** Redesigning the antivirus engine's malware-unpacking emulator from a pure interpreter into a hybrid LLVM-based JIT, making emulation up to 4x faster, plus an offline pre-translation scheme for firewalls and other constrained devices on AMD64 and AArch64.
- **Program analysis for vulnerability detection.** My PhD at the [University of British Columbia](https://www.ubc.ca), with [Karthik Pattabiraman](https://blogs.ubc.ca/karthik/) and [Julia Rubin](https://people.ece.ubc.ca/mjulia/), built static analysis techniques that find vulnerabilities by reasoning about root causes rather than matching code patterns, applied to Ethereum smart contracts. The work appeared at ICSE and ISSTA, and the tools ([SolidiFI](https://github.com/DependableSystemsLab/SolidiFI), [eTainter](https://github.com/DependableSystemsLab/eTainter), [AChecker](https://github.com/DependableSystemsLab/AChecker)) are open source.

Before the PhD, I completed two security-focused master's degrees, at the University of Victoria and KFUPM, with research on agentless security monitoring of computing hosts, behavior-based ransomware detection, and the security of SCADA systems, including attacks on live Siemens PLCs. My career began with several years in industry, building core banking software for microfinance institutions and running enterprise databases and ERP systems.
