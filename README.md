# Ziqi (`@Ziqi`)

**Systems, Security & Quantitative Infrastructure** · Beijing

Building deterministic, zero-trust infrastructure for AI-native environments, reproducible digital forensics (DFIR) toolchains, and quantitative market data pipelines.

---

### Flagship Open-Source Projects

| Project | Domain | Architecture & Supply-Chain Assurance |
| :--- | :--- | :--- |
| **[StarHub Kit](https://github.com/Ziqi/starhub-kit)** (`v1.1.0`) | AI-Native Mesh & Gateway Infrastructure | Zero-dependency declarative compiler (`Tier 0` drop-in YAML $\rightarrow$ `Tier 1` single-gateway $\rightarrow$ `Tier 2` full mesh) for `100.x + 4via6` Tailscale routing, surgical `Section 9a` QUIC (`UDP/443`) governance, and `B2` zero-SSH cloud AI sandbox isolation.<br/>[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16658/badge)](https://www.bestpractices.dev/projects/16658) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Ziqi/starhub-kit/badge)](https://scorecard.dev/viewer/?uri=github.com/Ziqi/starhub-kit) [![SLSA 3](https://slsa.dev/images/gh-badge-level3.svg)](https://github.com/Ziqi/starhub-kit/attestations) |
| **[StarShield Forensics](https://github.com/Ziqi/starshield-forensics)** (`v0.3.7`)<br/>[[Portal & Sample Workpaper](https://ziqi.github.io/starshield/)] | Digital Forensics & Incident Response (DFIR) | Deterministic offline Chromium LevelDB `.log` record carver (`OBSERVED` / `DERIVED` / `INFERRED` epistemic tiers), PNG/JPEG ICC display-pipeline provenance inspector, multi-rail financial checksum validator, and `StarShield-Bench-24` (`FSR-C-107` / `ISO 17025` dual-tool aligned).<br/>[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16602/badge)](https://www.bestpractices.dev/projects/16602) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Ziqi/starshield-forensics/badge)](https://scorecard.dev/viewer/?uri=github.com/Ziqi/starshield-forensics) [![PyPI](https://img.shields.io/pypi/v/starshield-forensics?label=PyPI%20%28PEP%20740%29&color=blue)](https://pypi.org/project/starshield-forensics/0.3.7/) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24145804.svg)](https://doi.org/10.5281/zenodo.24145804) [![SLSA 3](https://slsa.dev/images/gh-badge-level3.svg)](https://github.com/Ziqi/starshield-forensics/attestations) |
| **[KLine Kronos Suite](https://github.com/Ziqi/KLine-Kronos-Suite)** (`v1.0.1`) | Quantitative Time-Series Engineering | End-to-end 1-minute intraday OHLCV session cleaner, right-closed `1m -> 5m` aggregator, SHA-256 dataset QA auditor, and 5-stage `ttkbootstrap` fine-tuning & trading-calendar rollout workstation built around **[Kronos](https://github.com/shiyu-coder/Kronos)**.<br/>[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16679/badge)](https://www.bestpractices.dev/projects/16679) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Ziqi/KLine-Kronos-Suite/badge)](https://scorecard.dev/viewer/?uri=github.com/Ziqi/KLine-Kronos-Suite) [![SLSA 3](https://slsa.dev/images/gh-badge-level3.svg)](https://github.com/Ziqi/KLine-Kronos-Suite/attestations) [![CI & Coverage Gate](https://github.com/Ziqi/KLine-Kronos-Suite/actions/workflows/ci.yml/badge.svg)](https://github.com/Ziqi/KLine-Kronos-Suite/actions/workflows/ci.yml) |

---

### Standards & Community Contributions

- **OWASP GenAI Data Security Initiative** — Contributed bilingual (`EN` / `ZH`) financial-triage indirect prompt-injection test cases (`TC-0456`–`TC-0467`).
- **Supply-Chain & Verification Baseline** — Across all flagship repositories: `100%` GitHub Community Health, `SLSA Build Level 3` + offline `Ed25519` release signatures, `SPDX-2.3` SBOMs, `FSFE REUSE 3.2/3.3` licensing, `CodeQL` SAST, automated coverage/fuzz gates, and GitHub Private Vulnerability Reporting.

---

### 核心开源代表作（中文导览）

专注于 **AI 原生零信任基础设施**、**可复现电子数据取证（DFIR）** 与 **高频量化时序工程**：

- **[StarHub Kit (`v1.1.0`)](https://github.com/Ziqi/starhub-kit)**（**OpenSSF `Silver` 银牌认证 `#16658`** · Scorecard `8.1/10` · SLSA L3）：提供从「30 秒免编译 Mihomo × Tailscale 规则片段（Tier 0）」、「单网关双节点精简版（Tier 1）」到「云端 AI 沙箱 `B2` 零信任隔离（Tier 2）」的三级渐进式组网与透明网关编译套件，彻底根治 Fake-IP 环路与 Apple/Gmail `UDP/443` 卡死并保留电视端 YouTube 4K Cronet 加速。
- **[StarShield Forensics (`v0.3.7`)](https://github.com/Ziqi/starshield-forensics)**（**OpenSSF `Silver` 银牌认证 `#16602`** · PyPI `PEP 740` 可信发布 · Zenodo DOI `10.5281/zenodo.24145804` · [在线门户与脱敏底稿](https://ziqi.github.io/starshield/)）：纯离线零依赖 Chromium LevelDB `.log` 物理帧恢复、PNG/JPEG ICC 色彩链路溯源与跨境金融账号校验位核验工具集，配套 `FSR-C-107` / `ISO 17025` 双工具交叉验证报告。
- **[KLine Kronos Suite (`v1.0.1`)](https://github.com/Ziqi/KLine-Kronos-Suite)**（**OpenSSF `Silver` 银牌认证 `#16679`** · SLSA L3 · `90.29%` 核心覆盖率 + 2,000 轮属性模糊测试）：围绕金融基础模型 **Kronos** 打造的 1 分钟高频 K 线去噪清洗、右闭合 5 分钟重采样、SHA-256 质检打包与双阶段微调推演可视化套件（同时支持纯标准库 CLI 与桌面 GUI 工作台）。
