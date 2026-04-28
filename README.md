# Awesome On-Device Agents

A curated reading list for **on-device agents**, **mobile GUI automation**, and **efficient on-device / edge inference**.

This repository focuses on the intersection between two research questions:

1. How can agents perceive, reason, verify, and act on mobile devices and mobile apps?
2. How can language models and agent systems run efficiently under on-device constraints such as latency, memory, energy, and heterogeneous accelerators?

Efficient on-device inference is a prerequisite for practical on-device agents: without low-latency, memory-efficient, and energy-aware inference, agents cannot reliably run close to users, data, sensors, and apps. The list is intentionally selective and currently focuses on recent papers from 2024 onward, starting from work closely related to mobile agents, on-device inference, mobile automation, safety, and device-cloud collaboration.

## Scope

Included topics:

- Mobile GUI agents and Android task automation
- Efficient on-device LLM / SLM inference
- Safety, verification, and reliability for mobile agents
- Agent applications on mobile apps and mobile security
- Device-cloud and multi-device collaborative agents
- Broader edge intelligence papers that inform on-device agent systems
- Open-source systems for local inference, mobile AI engines, and device-cloud handoff

Out of scope:

- Generic web agents with no mobile or edge-device relevance
- Cloud-only agent systems with no mobile, edge, or deployment angle
- Pure model capability papers without relevance to mobile agents or on-device inference

## Taxonomy

```text
Awesome On-Device Agents
+-- Survey
+-- Efficient On-device Inference
+-- Mobile Agent Systems, Safety, and Applications
+-- Device-Cloud & Multi-device Collaboration
+-- Dataset & Benchmark
+-- Edge Intelligence
+-- Open-Source Systems
```

## Paper Index

### 1. Survey

| Paper | Date | Venue | Link |
|---|---:|---|---|
| Efficient Inference for Edge Large Language Models: A Survey | 2026 | TST | [Paper](https://doi.org/10.26599/TST.2025.9010166) |
| LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects | 2025.5 | arXiv | [Paper](https://arxiv.org/abs/2504.19838) |
| Mobile Edge Intelligence for Large Language Models: A Contemporary Survey | 2025.3 | COMST | [Paper](https://doi.org/10.1109/COMST.2025.3527641) |
| On-Device Language Models: A Comprehensive Review | 2024.8 | arXiv | [Paper](https://arxiv.org/abs/2409.00088) |
| Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security | 2024.1 | arXiv | [Paper](https://arxiv.org/abs/2401.05459) |

### 2. Efficient On-device Inference

| Paper | Date | Venue | Link |
|---|---:|---|---|
| Scaling LLM Test-Time Compute with Mobile NPU on Smartphones | 2026.4 | EuroSys | [Paper](https://doi.org/10.1145/3767295.3769382) |
| Elastic On-Device LLM Service | 2025.11 | MobiCom | [Paper](https://doi.org/10.1145/3680207.3765259) |
| D2MoE: Dual Routing and Dynamic Scheduling for Efficient On-Device MoE-based LLM Serving | 2025.11 | MobiCom | [Paper](https://doi.org/10.1145/3680207.3723493) |
| T-MAN: Enabling End-to-End Low-Bit LLM Inference on NPUs via Unified Table Lookup | 2025.11 | arXiv | [Paper](https://arxiv.org/abs/2511.11248) |
| Characterizing Mobile SoC for Accelerating Heterogeneous LLM Inference | 2025.10 | SOSP | [Paper](https://doi.org/10.1145/3731569.3764808) |
| EdgeMoE: Empowering Sparse Large Language Models on Mobile Devices | 2025.8 | TMC | [Paper](https://doi.org/10.1109/TMC.2025.3546466) |
| Neuralink: Fast on-Device LLM Inference with Neuron Co-Activation Linking | 2025.8 | ASPLOS | [Paper](https://doi.org/10.1145/3676642.3736114) |
| CLONE: Customizing LLMs for Efficient Latency-Aware Inference at the Edge | 2025.7 | ATC | [Paper](https://www.usenix.org/conference/atc25/presentation/tian) |
| EdgeLLM: Fast On-Device LLM Inference With Speculative Decoding | 2025.4 | TMC | [Paper](https://doi.org/10.1109/TMC.2024.3513457) |
| Fast On-device LLM Inference with NPUs | 2025.3 | ASPLOS | [Paper](https://doi.org/10.1145/3669940.3707239) |
| T-MAC: CPU Renaissance via Table Lookup for Low-Bit LLM Deployment on Edge | 2025.3 | EuroSys | [Paper](https://doi.org/10.1145/3689031.3696099) |
| PowerInfer-2: Fast Large Language Model Inference on a Smartphone | 2024.6 | arXiv | [Paper](https://arxiv.org/abs/2406.06282) |

### 3. Mobile Agent Systems, Safety, and Applications

| Paper | Date | Venue | Link |
|---|---:|---|---|
| Mobile GUI Agents under Real-world Threats: Are We There Yet? | 2026.4 | MobiSys | [Paper](https://doi.org/10.1145/3745756.3809249) |
| MANA: Towards Efficient Mobile Ad Detection via Multimodal Agentic UI Navigation | 2026.3 | MobiCom | [Paper](https://arxiv.org/abs/2603.20351) |
| VeriSafe Agent: Safeguarding Mobile GUI Agent via Logic-based Action Verification | 2025.11 | MobiCom | [Paper](https://doi.org/10.1145/3680207.3765248) |
| Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment | 2025.10 | MobiCom | [Paper](https://arxiv.org/abs/2503.15937) |
| AutoDroid-V2: Boosting SLM-based GUI Agents via Code Generation | 2025.6 | MobiSys | [Paper](https://doi.org/10.1145/3711875.3729134) |
| LLM-Explorer: Towards Efficient and Affordable LLM-based Exploration for Mobile Apps | 2025.5 | MobiCom | [Paper](https://arxiv.org/abs/2505.10593) |
| AutoDroid: LLM-powered Task Automation in Android | 2024.5 | MobiCom | [Paper](https://doi.org/10.1145/3636534.3649379) |

### 4. Device-Cloud & Multi-device Collaboration

| Paper | Date | Venue | Link |
|---|---:|---|---|
| EcoAgent: An Efficient Device-Cloud Collaborative Multi-Agent Framework for Mobile Automation | 2026 | AAAI | [Paper](https://doi.org/10.1609/aaai.v40i35.40230) |
| Jupiter: Fast and Resource-Efficient Collaborative Inference of Generative LLMs on Edge Devices | 2025.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM55648.2025.11044734) |
| Federated Adaptive Fine-Tuning of Large Language Models with Heterogeneous Quantization and LoRA | 2025.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM55648.2025.11044641) |
| Towards Federated Inference: An Online Model Ensemble Framework for Cooperative Edge AI | 2025.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM55648.2025.11044578) |
| EdgeShard: Efficient LLM Inference via Collaborative Edge Computing | 2025.5 | JIOT | [Paper](https://doi.org/10.1109/JIOT.2024.3524255) |
| Galaxy: A Resource-Efficient Collaborative Edge AI System for In-situ Transformer Inference | 2024.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM52122.2024.10621342) |

### 5. Dataset & Benchmark

| Paper | Date | Venue | Link |
|---|---:|---|---|
| AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents | 2025.7 | ACL | [Paper](https://aclanthology.org/2025.acl-long.107/) |
| AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents | 2025.4 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/01a83bc2f2732a58e6aa731e659e7101-Abstract-Conference.html) |
| MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents | 2024.6 | arXiv | [Paper](https://arxiv.org/abs/2406.08184) |

### 6. Edge Intelligence

| Paper | Date | Venue | Link |
|---|---:|---|---|
| Densing law of LLMs | 2025.11 | Nat. Mach. Intell. | [Paper](https://doi.org/10.1038/s42256-025-01137-0) |
| Intelligence per Watt: Measuring Intelligence Efficiency of Local AI | 2025.11 | arXiv | [Paper](https://arxiv.org/abs/2511.07885) |
| Small Language Models are the Future of Agentic AI | 2025.9 | arXiv | [Paper](https://arxiv.org/abs/2506.02153) |

## Open-Source Systems

| Project | Focus | Platform / Scope | Link |
|---|---|---|---|
| OmniInfer | Cross-platform local LLM/VLM inference engine with multi-backend support and OpenAI-compatible API server | Local inference across devices | [GitHub](https://github.com/omnimind-ai/OmniInfer) |
| Cactus | Low-latency AI engine for mobile devices and wearables, with multimodal APIs, ARM optimizations, and cloud fallback | Mobile and wearable AI | [GitHub](https://github.com/cactus-compute/cactus) |
| mLLM | Fast and lightweight multimodal LLM inference engine for mobile and edge devices, with Android, Jetson, and QNN/NPU support | Mobile and edge multimodal inference | [GitHub](https://github.com/UbiquitousLearning/mLLM) |
| Open-AutoGLM | Phone agent framework that uses VLM-based screen understanding, planning, and ADB-based device control for mobile task automation | Android phone agent | [GitHub](https://github.com/zai-org/Open-AutoGLM) |

## Notes

- The same paper may appear in more than one category when it is relevant to multiple themes.
- For arXiv papers, the venue column is updated when a formal conference or journal version can be verified.
- Open-source systems are listed separately from papers and are not treated as peer-reviewed publications.
- The current scope prioritizes recent work from 2024 onward.
- The current index is seeded by reviewed papers and should be expanded cautiously rather than treated as an exhaustive mobile-agent bibliography.

## Contribution

Contributions are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md).
