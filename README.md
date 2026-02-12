# The Luci Project: Central Ecosystem Hub

Welcome to **The Luci Project**, the central entry point for the **Wakanda Technologies 4.0** ecosystem. This repository aggregates the core components of the Nara Web 4.0 architecture.

Developed by **WPWakanda LLC** / Aevov AI Technologies.

## 🌌 Ecosystem Overview

The ecosystem is composed of several specialized repositories, each serving a distinct role in the **Hyper-Orchestration** stack.

| Component | Repository | License | Role |
| :--- | :--- | :--- | :--- |
| **Browser** | [**Lucia Browser**](lucia-browser/) | Hybrid (MIT/GPL) | The user-facing "Chromium-like" browser with spatial superpowers. |
| **Engine** | [**Nara Engine**](nara-engine/) | GPLv3 | The core orchestration backplane and UOE state machine. |
| **Logic** | [**ACL 3.0**](acl-3.0/) | GPLv3 | The Afolabi Computing Language interpreter (NeuroSymbolic logic). |
| **Network** | [**Quantum Mesh SDK**](quantum-mesh-sdk/) | MIT | SDK for building dApps on the QNS/HTTQ network. |
| **Theory** | [**AUF Intelligence**](auf-intelligence-suite/) | CC BY-NC-ND 4.0 | Core research papers and AFT/NRT theoretical models. |

## 🛠️ Getting Started

To clone the entire ecosystem, use the recursive flag:

```bash
git clone --recursive https://github.com/aevov/the-luci-project.git
cd the-luci-project
```

### Build Everything
Each submodule has its own build instructions, but generally:

1.  **Engine & Logic**: Rust-based (`cargo build --release`).
2.  **Browser**: Tauri-based (`cargo tauri build`).

## 🏛️ Architecture
The Luci Project represents the transition from the legacy "Web of Documents" to the **"Web of Cognitive Spaces"**.

- **Spatial Canvas**: A 3D coordinate system for organizing information.
- **Neural Linking**: AI-driven connections between disparate data points.
- **Quantum Identity**: Routing based on cryptographic keys, not IP addresses.

---
© 2026 WPWakanda LLC / Aevov AI Technologies.
*The Fourth Wave is here.* 🌊⚛️
