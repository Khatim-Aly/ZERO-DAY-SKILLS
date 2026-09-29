# ⚡ FL.Slayer — AI Agent Zero-Day Skills Roadmap

**A complete, interactive capability matrix for an AI agent built around vulnerability research, zero-day hunting, red team operations, and elite bug bounty work.**

> For authorized security research and AI agent capability design only.

---

## 📖 Overview

**AI Agent Zero-Day Skills Roadmap** is a single-page, self-contained HTML application that maps out the full capability tree an AI security-research agent needs to go from "understands how a computer works" to "finds and reports novel zero-day vulnerabilities."

It's built as a browsable, filterable reference — a capability spec / knowledge map you can consult when designing, scoping, or documenting what an autonomous or semi-autonomous security research agent should know, not a runnable tool and not step-by-step exploit instructions.

| Metric | Count |
|---|---|
| Domains | 13 |
| Skills | 90 |
| Techniques covered | 48+ |
| Tools referenced | 127+ |

## 🧭 Learning Phases

The roadmap is organized around six progressive phases:

1. **Foundation — Understand the Machine**
   x86-64 assembly, the memory model, C/C++, OS internals, networking fundamentals.
2. **Reverse Engineering — Read Without Source**
   Ghidra/IDA Pro, x64dbg/WinDbg, Frida, binary taxonomy, anti-analysis techniques.
3. **Vulnerability Classes — Know Bug Patterns**
   Buffer overflows, use-after-free, type confusion, integer overflows, race conditions.
4. **Discovery Techniques — Find New Bugs**
   Fuzzing (AFL++, libFuzzer), symbolic execution, taint analysis, code auditing, patch diffing (CodeQL).
5. **Exploitation — Turn Bugs into PoCs**
   ROP/JOP chains, heap feng shui, KASLR/ASLR bypass, sandbox escape, privilege escalation.
6. **Specialization — Target a Domain**
   Browser engines (V8/SpiderMonkey), Linux kernel, Android/iOS, RTOS/firmware, cloud APIs.

## 🗂️ Domain Matrix

| Domain | Focus | Skills |
|---|---|---|
| 🧠 Systems & Low-Level Foundations | Assembly, memory model, kernel/OS internals | 8 |
| 🔬 Reverse Engineering | Static/dynamic analysis of binaries & firmware | 8 |
| 💀 Vulnerability Classes | Every major bug class, from memory corruption to logic flaws | 15 |
| 🔫 Fuzzing & Automated Discovery | Coverage-guided fuzzing, symbolic execution, taint tracking | 8 |
| 🔍 Source Code Auditing | Manual & automated review before compilation | 7 |
| 💣 Exploit Development | Reliable PoCs, mitigation bypasses, exploit chaining | 7 |
| 🌐 Web Application Zero-Days | Beyond OWASP Top 10 | 9 |
| 📡 Network & Protocol Research | Zero-days in network stacks & infrastructure | 6 |
| 📱 Mobile & Embedded Zero-Days | iOS, Android, embedded device research | 5 |
| ☁️ Cloud & Container Research | Misconfig, container escape, serverless | 4 |
| 👁️ OSINT & Attack Surface Discovery | Target enumeration & intelligence gathering | 4 |
| 🤖 AI/LLM Security Research | Prompt injection, model theft, training data extraction | 4 |
| 📋 Disclosure, Reporting & Operations | Professional reporting & offensive tradecraft | 5 |

Each of the 90 skills includes:
- A short description and difficulty rating
- A difficulty/priority badge (`critical`, `high`, `core`, `advanced`)
- Relevant tags
- The specific tools used in practice
- A breakdown of what mastering that skill actually involves

**Badge distribution:** 32 critical · 38 high · 15 core · 5 advanced

## ✨ Features

- **Single HTML file** — no build step, no dependencies, works offline
- **Filterable** by priority (All / Critical / High / Advanced / Core)
- **Expandable skill cards** with tool lists and detailed breakdowns
- Clean, dark, terminal-inspired UI

## 🚀 Usage

Just open the file in any modern browser:

```bash
git clone https://github.com/<your-username>/ai-agent-zero-day-skills-roadmap.git
cd ai-agent-zero-day-skills-roadmap
open ai-agent-zero-day-skills.html   # or double-click it
```

No server, no build tools, no installation required.

## 🎯 Who This Is For

- Teams designing or scoping an AI agent for authorized security research / bug bounty work
- Security researchers moving from CTFs/bug bounty basics toward zero-day discovery
- Red teamers who want a structured map of offensive tradecraft
- Anyone building a personal or agent training/study plan for vulnerability research

## 🤖 A Note on "AI Agent"

This repo frames the skill matrix as a **capability reference** for what an AI security-research agent would need to know — it is a knowledge map, not an autonomous tool. It contains no exploit code, no attack automation, and no runnable payloads. Turning any of these entries into working tooling (fuzzers, exploit chains, agent tool-calling pipelines, etc.) is a separate engineering effort, governed by the same legal/ethical constraints as human-operated tools below.

## ⚠️ Disclaimer

This roadmap is provided strictly for **authorized security research, education, professional red team work, and legitimate AI agent capability design**. Techniques referenced here should only be applied to systems you own or are explicitly authorized to test — whether by a human or an agent acting on your behalf. Misuse of this material may violate the Computer Fraud and Abuse Act (US), the Computer Misuse Act (UK), or equivalent laws in your jurisdiction.

## 👤 Author

Created by **Khatim Ali**

## 📄 License
MIT
