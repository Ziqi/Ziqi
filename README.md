# Ziqi (`@Ziqi`)

**Systems, Security & Quantitative Infrastructure** · Beijing

Building deterministic, zero-dependency compilers for multi-site Tailscale networking and sandbox isolation, reproducible offline digital forensics (DFIR) toolchains, and quantitative market data pipelines.

---

## Open-Source Projects

| Project | Domain | Architecture & Supply-Chain Assurance |
| :--- | :--- | :--- |
| **[StarHub Kit](https://github.com/Ziqi/starhub-kit)** (`v1.2.0`) | Mesh & Sandbox Firewall Compiler | Zero-dependency declarative compiler (`brew install Ziqi/tap/starhub-kit` · `flake.nix` · `--only` modular `--dry-run` preview · bit-for-bit reproducible builds) for `100.x + 4via6` Tailscale routing, selective QUIC (`UDP/443`) rulesets, and zero-SSH cloud AI sandbox firewalls.<br/>[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16658/badge)](https://www.bestpractices.dev/projects/16658) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Ziqi/starhub-kit/badge)](https://scorecard.dev/viewer/?uri=github.com/Ziqi/starhub-kit) [![SLSA 3](https://slsa.dev/images/gh-badge-level3.svg)](https://github.com/Ziqi/starhub-kit/attestations) |
| **[StarShield Forensics](https://github.com/Ziqi/starshield-forensics)** (`v0.3.7`)<br/>[[Portal & Synthetic Benchmark](https://ziqi.github.io/starshield/)] | Digital Forensics & Incident Response (DFIR) | General-purpose, zero-dependency offline DFIR toolkit: deterministic Chromium LevelDB `.log` record carver (`uvx --from starshield-forensics starshield demo` · `OBSERVED` / `DERIVED` / `INFERRED` epistemic tiers), PNG/JPEG ICC display-pipeline provenance inspector, standard financial identifier checksum validator (IBAN/Luhn/ABA), and `StarShield-Bench-24` (`100%` synthetic validation corpus · `UK FSR Statutory Code FSA – DIG 100` & `ISO/IEC 17025` 482-vector dual-tool validation).<br/>[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16602/badge)](https://www.bestpractices.dev/projects/16602) [![OpenSSF Scorecard](https://img.shields.io/endpoint?url=https%3A%2F%2Fziqi.github.io%2Fstarshield%2Fscorecard.json)](https://scorecard.dev/viewer/?uri=github.com/Ziqi/starshield-forensics) [![PyPI](https://img.shields.io/pypi/v/starshield-forensics?label=PyPI%20%28PEP%20740%29&color=blue)](https://pypi.org/project/starshield-forensics/0.3.7/) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24145804.svg)](https://doi.org/10.5281/zenodo.24145804) [![SLSA 3](https://slsa.dev/images/gh-badge-level3.svg)](https://github.com/Ziqi/starshield-forensics/attestations) |
| **[KLine Kronos Suite](https://github.com/Ziqi/KLine-Kronos-Suite)** (`v1.1.0`) | Quantitative Time-Series Engineering | Zero-dependency 1-minute intraday OHLCV session cleaner (`kline-kronos demo` via `uvx` or `brew install Ziqi/tap/kline-kronos-suite`), right-closed `1m -> 5m` aggregator, SHA-256 dataset QA auditor, and 5-stage `ttkbootstrap` fine-tuning & China A-share trading-calendar rollout workstation built around **[Kronos](https://github.com/shiyu-coder/Kronos)**.<br/>[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16679/badge)](https://www.bestpractices.dev/projects/16679) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Ziqi/KLine-Kronos-Suite/badge)](https://scorecard.dev/viewer/?uri=github.com/Ziqi/KLine-Kronos-Suite) [![SLSA 3](https://slsa.dev/images/gh-badge-level3.svg)](https://github.com/Ziqi/KLine-Kronos-Suite/attestations) |

---

## Standards, Package Distribution & Community Contributions

- **Official Homebrew Tap ([`Ziqi/homebrew-tap`](https://github.com/Ziqi/homebrew-tap))** — One-command macOS & Linuxbrew installation from SLSA Level 3 reproducible source archives: `brew install Ziqi/tap/starhub-kit` and `brew install Ziqi/tap/kline-kronos-suite`.
- **OWASP GenAI Data Security Initiative** — Contributed bilingual (`EN` / `ZH`) financial-triage indirect prompt-injection test cases (`TC-0456`–`TC-0467`).
- **Supply-Chain & Verification Baseline** — Across all three repositories: `100%` GitHub Community Health, OpenSSF **Best Practices Silver**, **OSPS Baseline Level 3**, `SLSA Build Level 3` + offline `Ed25519` release signatures, `SPDX-2.3` SBOMs, `FSFE REUSE 3.2/3.3` licensing, `CodeQL` SAST, automated coverage/fuzz gates, and GitHub Private Vulnerability Reporting.

---

## 核心开源项目（中文导览）

专注于 **声明式异地组网与沙箱隔离工具链**、**可复现离线电子数据取证（DFIR）** 与 **高频量化时序工程**（支持官方 Homebrew 源 [`Ziqi/tap`](https://github.com/Ziqi/homebrew-tap) 一键安装）：

- **[StarHub Kit (`v1.2.0`)](https://github.com/Ziqi/starhub-kit)**（OpenSSF Silver `#16658` · SLSA L3 + OSPS Baseline L3）：支持 `brew install Ziqi/tap/starhub-kit`、原生 `flake.nix` 免安装运行及 `--only` 模块化无特权 `--dry-run` 预览，覆盖「免编译 Mihomo × Tailscale 规则包（Tier 0）」、「单网关精简版（Tier 1）」与「全栈多站点及云端 AI 沙箱双栈禁 SSH 隔离（Tier 2）」的确定性组网与防火墙编译器。
- **[StarShield Forensics (`v0.3.7`)](https://github.com/Ziqi/starshield-forensics)**（OpenSSF Silver `#16602` · PyPI `PEP 740` 可信发布 · Zenodo DOI `10.5281/zenodo.24145804` · [在线门户与合成基准报告](https://ziqi.github.io/starshield/)）：通用离线、零第三方依赖 DFIR 工具集，涵盖确定性 Chromium LevelDB `.log` 物理帧恢复、PNG/JPEG ICC 色彩链路溯源、标准金融标识符校验位（IBAN / Luhn / ABA）核验工具及 100% 合成验证语料库（`StarShield-Bench-24` · 对齐 `UK FSR 法定守则 FSA – DIG 100` 与 `ISO/IEC 17025` 482 向量双工具交叉验证，支持 `uvx --from starshield-forensics starshield demo` 零安装体验）。
- **[KLine Kronos Suite (`v1.1.0`)](https://github.com/Ziqi/KLine-Kronos-Suite)**（OpenSSF Silver `#16679` · SLSA L3 + OSPS Baseline L3 · `kline_kronos` 核心覆盖率 `91.15%` + 2,000 轮属性模糊测试）：围绕金融基础模型 **Kronos** 打造的 1 分钟高频 K 线去噪清洗、右闭合 5 分钟重采样、SHA-256 质检打包及五阶段 `ttkbootstrap` 桌面微调推演工作台（支持 `uvx --from git+https://github.com/Ziqi/KLine-Kronos-Suite kline-kronos demo` 与 `brew install Ziqi/tap/kline-kronos-suite` 免克隆体验）。
