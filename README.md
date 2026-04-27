# Awesome Mobile Agents

A curated reading list for **mobile agents**, **mobile GUI automation**, and **efficient on-device / edge inference**.

This repository focuses on the intersection between two research questions:

1. How can agents perceive, reason, verify, and act on mobile devices and mobile apps?
2. How can language models and agent systems run efficiently under on-device constraints such as latency, memory, energy, and heterogeneous accelerators?

The list is intentionally selective. It starts from papers that are closely related to mobile agents, on-device inference, mobile automation, safety, and device-cloud collaboration.

## Scope

Included topics:

- Mobile GUI agents and Android task automation
- Efficient on-device LLM / SLM inference
- Safety, verification, and reliability for mobile agents
- Agent applications on mobile apps and mobile security
- Device-cloud and multi-device collaborative agents
- Broader edge intelligence papers that inform on-device agent systems

Out of scope:

- Generic web agents with no mobile or edge-device relevance
- Cloud-only agent systems with no mobile, edge, or deployment angle
- Pure model capability papers without relevance to mobile agents or on-device inference

## Taxonomy

```text
Awesome Mobile Agents
+-- Survey
+-- Efficient On-device Inference
+-- Mobile GUI Agents and Android Task Automation
+-- Security
+-- Application
+-- Device-Cloud & Multi-device Collaboration
+-- Edge Intelligence
```

## Paper Index

### 1. Survey

| Paper | Year | Venue / Journal | Link |
|---|---:|---|---|
| LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects | 2025 | TMLR | [TMLR](https://openreview.net/forum?id=c9g0OpnP7o) |
| Mobile Edge Intelligence for Large Language Models: A Contemporary Survey | 2025 | IEEE Communications Surveys & Tutorials | [IEEE Xplore](https://ieeexplore.ieee.org/document/10835069) |
| On-Device Language Models: A Comprehensive Review | 2024 | arXiv | [arXiv](https://arxiv.org/abs/2409.00088) |
| Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security | 2024 | arXiv | [arXiv](https://arxiv.org/abs/2401.05459) |

### 2. Efficient On-device Inference

| Paper | Year | Venue / Journal | Link |
|---|---:|---|---|
| PowerInfer-2: Fast Large Language Model Inference on a Smartphone | 2024 | arXiv | [arXiv](https://arxiv.org/abs/2406.06282) |
| Fast On-device LLM Inference with NPUs | 2025 | ASPLOS | [ACM DL](https://dl.acm.org/doi/10.1145/3669940.3707255) |
| Elastic On-Device LLM Service | 2025 | ACM MobiCom | [ACM DL](https://dl.acm.org/doi/10.1145/3711875.3729133) |
| EdgeLLM: Fast On-Device LLM Inference With Speculative Decoding | 2025 | IEEE Transactions on Mobile Computing | [IEEE Xplore](https://ieeexplore.ieee.org/document/10858427) |
| EdgeMoE: Empowering Sparse Large Language Models on Mobile Devices | 2025 | IEEE Transactions on Mobile Computing | [IEEE Xplore](https://ieeexplore.ieee.org/document/10856570) |
| Neuralink: Fast on-Device LLM Inference with Neuron Co-Activation Linking | 2025 | ASPLOS | [ACM DL](https://dl.acm.org/doi/10.1145/3676642.3736114) |
| D2MoE: Dual Routing and Dynamic Scheduling for Efficient On-Device MoE-based LLM Serving | 2025 | ACM MobiCom | [ACM DL](https://dl.acm.org/doi/10.1145/3711875.3729168) |
| CLONE: Customizing LLMs for Efficient Latency-Aware Inference at the Edge | 2025 | USENIX ATC | [USENIX](https://www.usenix.org/conference/atc25/presentation/tian) |
| HeteroLLM: Accelerating Large Language Model Inference on Mobile SoCs with Heterogeneous AI Accelerators | 2025 | SOSP | [arXiv](https://arxiv.org/abs/2505.14788) |
| T-MAC: CPU Renaissance via Table Lookup for Low-Bit LLM Deployment on Edge | 2025 | EuroSys | [ACM DL](https://dl.acm.org/doi/10.1145/3689031.3696074) |
| T-MAN: Enabling End-to-End Low-Bit LLM Inference on NPUs via Unified Table Lookup | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2505.17843) |
| Scaling LLM Test-Time Compute with Mobile NPU on Smartphones | 2026 | EuroSys | [ACM DL](https://dl.acm.org/doi/10.1145/3715336.3735835) |

### 3. Mobile GUI Agents and Android Task Automation

| Paper | Year | Venue / Journal | Link |
|---|---:|---|---|
| Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment | 2026 | ACM MobiCom | [Microsoft Research](https://www.microsoft.com/en-us/research/publication/advancing-mobile-gui-agents-a-verifier-driven-approach-to-practical-deployment/) |
| AutoDroid-V2: Boosting SLM-based GUI Agents via Code Generation | 2025 | ACM MobiSys | [ACM DL](https://dl.acm.org/doi/10.1145/3711875.3729134) |
| AutoDroid: LLM-powered Task Automation in Android | 2024 | ACM MobiCom | [ACM DL](https://dl.acm.org/doi/10.1145/3636534.3649379) |

### 4. Security

| Paper | Year | Venue / Journal | Link |
|---|---:|---|---|
| Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment | 2026 | ACM MobiCom | [Microsoft Research](https://www.microsoft.com/en-us/research/publication/advancing-mobile-gui-agents-a-verifier-driven-approach-to-practical-deployment/) |
| AutoDroid-V2: Boosting SLM-based GUI Agents via Code Generation | 2025 | ACM MobiSys | [ACM DL](https://dl.acm.org/doi/10.1145/3711875.3729134) |
| AutoDroid: LLM-powered Task Automation in Android | 2024 | ACM MobiCom | [ACM DL](https://dl.acm.org/doi/10.1145/3636534.3649379) |

### 5. Application

| Paper | Year | Venue / Journal | Link |
|---|---:|---|---|
| LLM-Explorer: Towards Efficient and Affordable LLM-based Exploration for Mobile Apps | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2505.10593) |
| MANA: Towards Efficient Mobile Ad Detection via Multimodal Agentic UI Navigation | 2026 | arXiv | [arXiv](https://arxiv.org/abs/2603.20351) |

### 6. Device-Cloud & Multi-device Collaboration

| Paper | Year | Venue / Journal | Link |
|---|---:|---|---|
| EcoAgent: An Efficient Device-Cloud Collaborative Multi-Agent Framework for Mobile Automation | 2026 | AAAI | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/38088) |

### 7. Edge Intelligence

| Paper | Year | Venue / Journal | Link |
|---|---:|---|---|
| Small Language Models are the Future of Agentic AI | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2506.02153) |

## Notes

- The same paper may appear in more than one category when it is relevant to multiple themes.
- For arXiv papers, the venue column is updated when a formal conference or journal version can be verified.
- The current index is seeded by reviewed papers and should be expanded cautiously rather than treated as an exhaustive mobile-agent bibliography.

## Contribution

Contributions are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md).
