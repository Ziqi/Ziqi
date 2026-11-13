# Ziqi (`@Ziqi`)

**Systems, Security & Quantitative Infrastructure** · Beijing

Building deterministic, zero-trust infrastructure for AI-native environments, reproducible digital forensics (DFIR) toolchains, and quantitative market data pipelines.

---

### Flagship Open-Source Projects

| Project | Domain | Highlights & Supply-Chain Assurance |
| :--- | :--- | :--- |
| **[StarHub Kit](https://github.com/Ziqi/starhub-kit)** | AI-Native Mesh & Gateway Infrastructure | Zero-dependency declarative compiler for `100.x + 4via6` Tailscale meshes, anti-stall Fake-IP / selective QUIC (`UDP/443`) transparent gateways, and `B2` zero-SSH cloud AI sandbox isolation.<br/>[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16658/badge)](https://www.bestpractices.dev/projects/16658) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Ziqi/starhub-kit/badge)](https://scorecard.dev/viewer/?uri=github.com/Ziqi/starhub-kit) |
| **[StarShield Forensics](https://github.com/Ziqi/starshield-forensics)**<br/>[[Documentation & Workpaper Portal](https://ziqi.github.io/starshield/)] | Digital Forensics & Incident Response (DFIR) | Deterministic offline Chromium LevelDB `.log` record carver, PNG/JPEG ICC display-pipeline provenance inspector, multi-rail financial checksum validator, and the `StarShield-Bench-24` validation suite (`MIT`). |
| **[KLine Kronos Suite](https://github.com/Ziqi/KLine-Kronos-Suite)** | Quantitative Time-Series Engineering | End-to-end 1-minute to multi-timeframe OHLCV acquisition, resampling, sliding-window tensor slicing, and fine-tuning/inference workstation built around financial foundation models. |

---

### Standards & Community Contributions

- **OWASP GenAI Data Security Initiative** — Contributed bilingual (EN/ZH) financial-triage indirect prompt-injection test cases (`TC-0456`–`TC-0467`).
- **Engineering Principles** — Single Source of Truth (SSOT) declarative compilation, zero external runtime dependencies on privileged boundaries, cryptographic release provenance (`SLSA Build Level 3` + offline `Ed25519` + `SPDX-2.3` SBOM), and automated drift/fuzz gates.

---

### 核心开源方向（中文简介）

专注于 **AI 原生零信任基础设施**、**离线电子数据取证（DFIR）** 与 **高频量化时序工程**：

- **[StarHub Kit](https://github.com/Ziqi/starhub-kit)**（获颁 **OpenSSF Best Practices `Silver` 银牌认证 `#16658`** · Scorecard `8.1/10`）：零第三方依赖声明式跨城组网与透明网关编译套件，系统性解决 Tailscale × Fake-IP 路由回环、Apple/Gmail 精确 QUIC 降级与 YouTube 4K Cronet 共存、以及云端 AI 沙盒 `B2` 禁 SSH 零信任隔离。
- **[StarShield Forensics](https://github.com/Ziqi/starshield-forensics)**（[在线门户与脱敏底稿](https://ziqi.github.io/starshield/)）：纯离线确定性 Chromium LevelDB 日志物理恢复、PNG/JPEG ICC 色彩链路溯源与金融校验位核验工具集。
