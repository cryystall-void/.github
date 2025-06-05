# 🧠 Void C++ Team

Welcome to the **Void C++ Team**, the internal engineering group responsible for the core C++ components of **Void** — a modular, high-performance deep reinforcement learning (DRL) agent.

Our work supports the simulation, logging, and common infrastructure required for scalable RL experimentation, written entirely in modern C++.

---

## 🛰️ Mission

We build the foundational systems that drive Void's learning and simulation capabilities.

All components are:

- **Native C++** — no scripting or bindings
- **Modular** — designed for reuse across subprojects
- **Performance-focused** — optimized for high-throughput environments

---

## 📦 Internal Projects

| Project | Description |
|---------|-------------|
| **Void_Status** | Computes structured features and derived properties from raw environment states. |
| **Void_Logging** | Logs environment data, reward metrics, and agent signals for analysis and debugging. |
| **Void_Utils** | Shared utility code used across all modules (e.g., config parsing, timing, math helpers). |
| **Void_Common** | Common types, enums, and interfaces used by Void’s submodel projects. |

All repositories are **private** and intended for internal use within the organization.

---

## 🛠️ Tech Stack

- **C++20**
- **CMake** for builds
- **Catch2** for unit testing
- **LibTorch** for deep learning modules
- [**RLGymSim_CPP**](https://github.com/ZealanL/RLGymSim_CPP) for environment simulation
- [**RLGymPPO_CPP**](https://github.com/ZealanL/RLGymPPO_CPP) for training agents

---

## 🔗 Architecture Overview

Void is composed of multiple specialized modules that communicate via shared data structures and logging conventions. Each module is focused, testable, and reusable.

This architecture enables:

- Rapid prototyping of submodels
- Clear boundaries and separation of concerns
- Scalable experimentation in reinforcement learning

---

## 📚 Access & Development

These projects are internal and restricted to authorized contributors.

- Access is managed via organization-level permissions.
- Development follows internal C++ standards and review protocols.
- For new contributors, see the internal onboarding documentation or contact a team lead.

---

## 🔒 License

All projects are licensed under the **MIT License** for internal use only.

---

© [cryystall-void], maintained by the Void C++ Team.
