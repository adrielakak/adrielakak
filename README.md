<div align="center">

<img src="./assets/widescreen-tunnel.gif" width="100%" alt="3D Perspective Tunnel — Real ASCII Geometry" />

# Adriel Kourlate
**Data Science · Quantitative ML · Systems & AI Engineering**

<sub>Dual-degree Centrale Nantes × Audencia · Visiting Shenzhen University</sub>

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-adrielkourlate.vercel.app-0b0f17?style=flat-square&logo=vercel&logoColor=white&labelColor=1a2234)](https://portfolio-nu-eosin-a953g7hsv2.vercel.app)
[![GravityNotch](https://img.shields.io/badge/macOS_App-GravityNotch-0b0f17?style=flat-square&logo=apple&logoColor=white&labelColor=1a2234)](https://github.com/adrielakak/GravityNotch)
[![Adastra](https://img.shields.io/badge/FinTechathon-Adastra_ML_Cockpit-0b0f17?style=flat-square&logo=python&logoColor=10b981&labelColor=1a2234)](https://webank-tawny.vercel.app)
[![SQL Report](https://img.shields.io/badge/SQL_Project-Train_DB_Report-0b0f17?style=flat-square&logo=postgresql&logoColor=38bdf8&labelColor=1a2234)](https://portfolio-nu-eosin-a953g7hsv2.vercel.app/projects/DB_Lab_2_AdrielKourlate.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Adriel_Kourlate-0b0f17?style=flat-square&logo=linkedin&logoColor=0ea5e9&labelColor=1a2234)](https://www.linkedin.com/in/adriel-kourlate-28033032b/)
[![Contact](https://img.shields.io/badge/Contact-adriel.kourlate5%40audencia.com-0b0f17?style=flat-square&logo=gmail&logoColor=fb7185&labelColor=1a2234)](mailto:adriel.kourlate5@audencia.com)

</div>

<br />

### 🔬 Selected Work & Engineering

#### 01 / [GravityNotch: a Dynamic Island for the MacBook Notch](https://github.com/adrielakak/GravityNotch)
*Native macOS app · Built in close collaboration with AI coding agents*
- **Lock Screen Media Player:** Tapping the cover turns it into a full screen wallpaper, using the Apple Music animated artwork when it exists (HLS variant selection, local caching, seamless looping in up to 2160p).
- **Live Coding Agent Monitor:** Follows Claude Code, Codex and Antigravity sessions from the notch, with pixel mascots, a progress checklist, diff counters and a speech bubble when an agent finishes or needs input.
- **AI-Augmented Engineering:** Fork of the open source boring.notch, extended feature by feature by directing AI agents: I set the product vision, test on real hardware and iterate, which lets one student ship what would normally take a small team.
- `Swift` `SwiftUI` `AppKit` `AVFoundation` `AppleScript` `Claude Code`
- 🔗 **[GitHub Repository](https://github.com/adrielakak/GravityNotch)**

<br />

#### 02 / [llm-dedup-rs — High-Performance LLM Dataset Cleaning & MinHash LSH in Rust](https://github.com/adrielakak/llm-dedup-rs)
*Systems & Data Engineering · Rust (`PyO3` + `Rayon`) exposed natively to Python*
- **GIL-Free Speedup (`337.9×`–`521.9×`):** Replaces Python loops with compiled LLVM Rust, `FxHash` 64-bit exact deduplication, and flat contiguous `Vec<u32>` MinHash LSH signatures parallelized across 10 cores (`314,989 docs/s`).
- **Memory & Quality Pipeline:** Cuts net RAM overhead by **69.2%** on 20k documents (`40.69 MiB` vs `132.25 MiB` in pure Python) while performing HTML stripping, quality filtering, exact and fuzzy deduplication (`threshold = 0.80`).
- `Rust` `PyO3` `Rayon` `Python` `MinHash` `LSH` `Maturin`
- 🔗 **[GitHub Repository](https://github.com/adrielakak/llm-dedup-rs)**

<br />

#### 03 / [AutoPilot FSD — Autonomous Driving Simulation via NEAT Neuroevolution](https://github.com/adrielakak/autopilot)
*Reinforcement / Neuroevolution · Real-Time 2D Physics & 3D WebGL Telemetry*
- **Physics & Semantic LIDAR:** Custom 2D octagonal track engine (`800×800`) with exact circle-segment and circle-OBB swept collision checks, 15-channel semantic LIDAR (`Wall`, `NPC`, `STOP`), and regulatory STOP-zone logic.
- **Real-Time Architecture:** Asynchronous **FastAPI** simulation server streaming 60 Hz WebSocket telemetry to a **React 19 + TypeScript + Three.js** cockpit (`1×`–`10×` speed, NEAT swarm visualization, fitness curves).
- `Python` `NEAT` `FastAPI` `WebSockets` `React 19` `TypeScript` `Three.js`
- 🔗 **[GitHub Repository](https://github.com/adrielakak/autopilot)**

<br />

#### 04 / [Herculaneum Papyrus Ink Detection on Apple Silicon (MPS)](https://github.com/adrielakak/herculaneum-ink-mps)
*Computer Vision & Scientific Reproduction · Vesuvius Challenge (`ink_9um`)*
- **Local Apple M4 MPS Evaluation:** End-to-end 3D/2D inference pipeline running `scrollprize/ink_9um` on Apple Silicon (`PyTorch` MPS, 16 GB RAM) using custom C++ `vc_reader` bindings without CUDA.
- **Memorization vs. Generalization Protocol:** Verified memorization on training segment `PHerc0139 w035` (`PR-AUC 0.9981`) and rigorously evaluated generalization on unseen scroll `PHerc0841 w00` (`PR-AUC 0.7121`, `ROC-AUC 0.8531` within `supervision.zarr`).
- `Python` `PyTorch` `Apple MPS` `Computer Vision` `Zarr` `Vesuvius Challenge`
- 🔗 **[GitHub Repository](https://github.com/adrielakak/herculaneum-ink-mps)**

<br />

#### 05 / [Adastra — Quantitative Risk Intelligence & Allocation Cockpit](https://github.com/adrielakak/webank)
*FinTechathon 2026 (WeBank Track) · Shenzhen University*
- **Explainable Gradient Boosting & Behavioral Finance:** Walk-forward validated cost-sensitive **LightGBM** pipelines paired with exact **TreeSHAP** risk attribution, orthogonal news shocks, and Kahneman-Tversky peer modeling across China A-Shares.
- **Compliance & Audit Architecture:** CSRC `R1`–`R5` suitability classification with asymmetric tail-risk guardrails and timestamped SHA-256 audit seals served via **FastAPI** and **React 18**.
- `Python` `LightGBM` `TreeSHAP` `FastAPI` `React` `Quantitative Finance`
- 🔗 **[Live Cockpit Demo](https://webank-tawny.vercel.app)** · **[GitHub Repository](https://github.com/adrielakak/webank)**

<br />

#### 06 / [Train DB — Railway SQL System & Relational Architecture](https://portfolio-nu-eosin-a953g7hsv2.vercel.app/projects/DB_Lab_2_AdrielKourlate.pdf)
*Relational Database Modeling & Query Optimization*
- **Data Architecture:** Designed complete conceptual (ERD) and logical (MLD) schemas normalized to **3rd Normal Form (3NF)** across 14 interconnected relations.
- **Query Engineering & Audit:** Implemented multi-table analytical joins, index tuning, composite foreign key constraints, and transactional consistency validation.
- `PostgreSQL` `SQL Optimization` `ERD / MLD` `Data Quality Audit`
- 🔗 **[Full Engineering Report (PDF)](https://portfolio-nu-eosin-a953g7hsv2.vercel.app/projects/DB_Lab_2_AdrielKourlate.pdf)**

<br />

#### 07 / [Electoral Dynamics (2002–2022)](https://github.com/adrielakak/project-election)
*Statistical & Geospatial Data Science*
- **20-Year Longitudinal Study:** Department-level econometric analysis tracking French presidential voter turnout, abstention trends, and geographical political realignments.
- **Geospatial Modeling:** Processed multi-decade electoral datasets with automated GeoJSON spatial joins, choropleth mapping, and interactive Plotly visual analytics.
- `Python` `Pandas` `Plotly` `GeoJSON` `Statistical Analysis`
- 🔗 **[GitHub Repository](https://github.com/adrielakak/project-election)**

<br />

#### 08 / [Personal Portfolio & Interactive Case Studies](https://portfolio-nu-eosin-a953g7hsv2.vercel.app)
*Interactive Web & Data Systems Showcase*
- **Engineering Showcase:** Bilingual platform presenting database architecture reports, statistical notebooks, and quantitative ML implementations.
- **Creative Web:** Custom Three.js background shaders and GSAP animations running at 60 fps.
- `JavaScript` `Three.js` `GSAP` `Vercel`
- 🔗 **[Explore Portfolio](https://portfolio-nu-eosin-a953g7hsv2.vercel.app)** · **[GitHub Repository](https://github.com/adrielakak/Portfolio)**
