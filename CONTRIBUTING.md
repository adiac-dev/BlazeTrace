# Contributing to BlazeTrace

Thanks for your interest in **BlazeTrace** — the open-source engine that connects **eBPF runtime traces** to **Git commits** with **AI-powered root cause analysis**.

We welcome contributions of all kinds: code, docs, bug reports, ideas, and even memes.

---

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Project Structure](#project-structure)
- [eBPF Guidelines](#ebpf-guidelines-critical)
- [AI & Prompts](#ai--prompts)
- [Testing](#testing)
- [Pull Requests](#pull-requests)
- [Release Process](#release-process)
- [Need Help?](#need-help)

---

## Code of Conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct.html).  
Be respectful, inclusive, and kind.

---

## How to Contribute

| You can help with |
|-------------------|
| Report a bug (`/issues`) |
| Suggest a feature (`/issues`) |
| Improve docs or examples |
| Add eBPF probes (HTTP, DB, crypto, etc.) |
| Optimize the Git blame engine |
| Build VS Code / JetBrains plugins |
| Write AI prompts or ML models |
| Translate README to other languages |

---

## Development Setup

```bash
# 1. Fork & clone
git clone https://github.com/yourname/blazetrace.git
cd BlazeTrace

# 2. Install tools
just bootstrap   # uses justfile — installs Rust, Python, Docker, Ollama

# 3. Run demo
just demo        # starts go-app + codepulse watch
