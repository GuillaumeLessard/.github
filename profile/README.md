<p align="center">
  <img src="logo_banner.png" alt="QECTOR Logo" width="80%" />
</p>

<h1 align="center">QECTOR</h1>

<p align="center">
  <strong>High-Performance Quantum Error Correction</strong><br/>
  <em>Independent QEC Research &amp; Development · Rust + Python Decoding Platform</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/engine-qector--decoder--v3_1.0.0-E44D26?style=for-the-badge&logo=rust&logoColor=white" alt="Engine"/>
  <img src="https://img.shields.io/badge/Workbench-v1.0.1-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Workbench"/>
  <img src="https://img.shields.io/badge/Claude_Plugin-v1.0.2-8A2BE2?style=for-the-badge&logo=anthropic&logoColor=white" alt="Plugin"/>
  <img src="https://img.shields.io/badge/decoders-17-success?style=for-the-badge" alt="Decoders"/>
  <img src="https://img.shields.io/badge/license-Source--Available-FFA500?style=for-the-badge" alt="License"/>
</p>

<p align="center">
  <a href="https://www.qector.store">Website</a> ·
  <a href="#-ecosystem">Ecosystem</a> ·
  <a href="#-current-status">Status</a> ·
  <a href="#-licensing">Licensing</a> ·
  <a href="#-contact">Contact</a>
</p>

---

## 📖 Overview

**QECTOR** is a proprietary, production-grade **quantum error correction** engineering and research platform built on the high-performance `qector-decoder-v3` Rust/PyO3 engine. Every syndrome decoding is mathematically verified ($H c \equiv s \pmod 2$), fail-closed, and runs **100% offline with zero network egress**.

- **17 specialized decoding backends** — MWPM/Blossom, BP-OSD, Hybrid, Neural, two-stage, space-time and more
- **10 code families** — surface, heavy-hex, toric, qLDPC (bicycle / bivariate bicycle), hypergraph product, color codes
- **Hardware acceleration** — CUDA and OpenCL batch processing, streaming, edge-optimized paths
- **Security-first** — offline, zero-egress execution architecture
- **Ecosystem compatible** — integrates with Stim, Sinter, PyMatching, Qiskit and Claude workflows
- **Reproducible** — SHA-256 manifests on every export, exact Wilson 95% confidence intervals on every LER sweep

---

## 🧩 Ecosystem

| Project | Status | Highlights |
|:--------|:-------|:-----------|
| **QECTOR Decoder v3** (engine) | v1.0.0 | Proprietary Rust/PyO3 decoding engine — [PyPI](https://pypi.org/project/qector-decoder-v3/) |
| **QECTOR Decoder Workbench — Windows** | v1.0.1 | Portable `.exe`, 85-tool MCP server — [Releases](https://github.com/qectorlab/qector-decoder-workbench-windows/releases/tag/v1.0.1) |
| **QECTOR Decoder Workbench — Linux** | v1.0.1 | AppImage, 85-tool MCP server — [Releases](https://github.com/qectorlab/qector-decoder-workbench-linux/releases/tag/v1.0.1) |
| **QECTOR Decoder Workbench — macOS** | build pending | Requires Apple hardware build & signing |
| **QECTOR Claude Plugin** | v1.0.2 | 2 MCP servers (37 tools), 13 commands, 5 agents, 28 skills — [Repository](https://github.com/GuillaumeLessard/qector-claude-plugin) |

---

## 📖 Current Status (August 2026)

- ✅ **v1.0.1 workbench releases** shipped for Windows and Linux (portable `.exe` + AppImage), air-gapped, zero-install
- ✅ **v1.0.0 engine** released — enterprise-grade, simulation-validated, GPU-accelerated
- ✅ **Claude Code / Claude Desktop plugin v1.0.2** — fully compatible with both workbench releases
- ✅ **85-tool stdio MCP server** in every workbench release; no HTTP bridge, no port binding
- 🔄 Signed release attestations and reproducible-build provenance in development

---

## 📚 Documentation

| Resource | Location |
|:---------|:---------|
| API Reference (MD / HTML / PDF) | In every workbench release package (`manuals/`) |
| MCP Integration Guide | In every workbench release package (`manuals/`) |
| LLM Reference Manual (`QECTOR_LLM_Manual.json`) | In every workbench release package (`manuals/`) |
| QECTOR Decoder v3 Reference Manual v1.0.0 | DOI `10.5281/zenodo.21941046` |

---

## 💼 Licensing

### Backend (`qector-decoder-v3`)

Source-available Rust/Python platform:

- ✅ **Free** for personal, academic, educational, and non-commercial research
- 💼 **Commercial use** (company R&D, SaaS, hosted API, OEM, redistribution) **requires a [paid license](https://qector.store/pricing)**
- 🔄 60-day commercial evaluation available, creditable against a license

### Workbench & Plugin

Source-available; commercial use requires a paid license. See the `EULA.txt`
shipped with each release and [LICENSE.md](https://github.com/GuillaumeLessard/qector-claude-plugin/blob/main/LICENSE.md).

---

## 📫 Contact

| | |
|:--|:--|
| **Website** | [www.qector.store](https://www.qector.store) |
| **Commercial Licensing** | [admin@qector.store](mailto:admin@qector.store) |
| **Support** | [admin@qector.store](mailto:admin@qector.store) |
| **Pricing** | [qector.store/pricing](https://qector.store/pricing) |

---

<p align="center">
  <strong>QECTOR</strong><br/>
  © 2026 Guillaume Lessard / iD01t Productions<br/>
  ORCID <a href="https://orcid.org/0009-0000-3465-3753">0009-0000-3465-3753</a><br/><br/>
  <em>Building reliable, verified tools to accelerate fault-tolerant quantum computing research.</em>
</p>