# Awesome On-Device Agents

[English](README.md)

一个整理 **端侧智能体**、**移动端 GUI 自动化** 和 **高效端侧 / 边缘推理** 相关论文与资源的阅读列表。

本仓库关注两个相互交叉的研究问题：

1. 智能体如何在移动设备和移动应用上感知、推理、验证并执行操作？
2. 在时延、内存、能耗和异构加速器等端侧约束下，语言模型和智能体系统如何高效运行？

高效端侧推理是实用端侧智能体的前提：如果没有低时延、低内存占用和能耗友好的推理能力，智能体就难以可靠地贴近用户、数据、传感器和应用运行。本列表是一个有选择性的论文库，目前优先收录 2024 年以来与移动智能体、端侧推理、移动自动化、安全和端云协同相关的工作。

## 范围

收录主题：

- 移动端 GUI 智能体和 Android 任务自动化
- 高效端侧 LLM / SLM 推理
- 移动智能体的安全、验证和可靠性
- 移动应用和移动安全中的智能体应用
- 端云协同和多设备协同智能体
- 对端侧智能体系统有启发的边缘智能相关工作
- 本地推理、移动 AI 引擎和端云切换相关的开源系统

暂不收录：

- 与移动端或边缘设备无关的通用 Web 智能体
- 没有端侧、移动端或边缘部署视角的纯云端智能体系统
- 与智能体、移动系统或端侧推理无关的纯模型能力论文

## 目录

- [论文索引](#论文索引)
  - [综述](#1-综述)
  - [高效端侧推理](#2-高效端侧推理)
  - [移动智能体系统、安全与应用](#3-移动智能体系统安全与应用)
  - [端云与多设备协同](#4-端云与多设备协同)
  - [数据集与基准](#5-数据集与基准)
  - [边缘智能（扩展阅读）](#6-边缘智能扩展阅读)
- [开源系统](#开源系统)
- [说明](#说明)
- [贡献](#贡献)

## 分类

```text
Awesome On-Device Agents
+-- 综述
+-- 高效端侧推理
+-- 移动智能体系统、安全与应用
+-- 端云与多设备协同
+-- 数据集与基准
+-- 边缘智能
+-- 开源系统
```

## 论文索引

### 1. 综述

| 论文 | 日期 | 会议/期刊 | 链接 |
|---|---:|---|---|
| Efficient Inference for Edge Large Language Models: A Survey | 2026.6 | TST | [Paper](https://doi.org/10.26599/TST.2025.9010166) |
| GUI Agents: A Survey | 2025.7 | Findings ACL | [Paper](https://aclanthology.org/2025.findings-acl.1158/) |
| LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects | 2025.5 | arXiv | [Paper](https://arxiv.org/abs/2504.19838) |
| Mobile Edge Intelligence for Large Language Models: A Contemporary Survey | 2025.3 | COMST | [Paper](https://doi.org/10.1109/COMST.2025.3527641) |
| On-Device Language Models: A Comprehensive Review | 2024.8 | arXiv | [Paper](https://arxiv.org/abs/2409.00088) |
| Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security | 2024.1 | arXiv | [Paper](https://arxiv.org/abs/2401.05459) |

### 2. 高效端侧推理

| 论文 | 日期 | 会议/期刊 | 链接 |
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

### 3. 移动智能体系统、安全与应用

| 论文 | 日期 | 会议/期刊 | 链接 |
|---|---:|---|---|
| Mobile GUI Agents under Real-world Threats: Are We There Yet? | 2026.4 | MobiSys | [Paper](https://arxiv.org/abs/2507.04227) |
| MANA: Towards Efficient Mobile Ad Detection via Multimodal Agentic UI Navigation | 2026.3 | MobiCom | [Paper](https://arxiv.org/abs/2603.20351) |
| AgentProg: Empowering Long-Horizon GUI Agents with Program-Guided Context Management | 2025.12 | arXiv | [Paper](https://arxiv.org/abs/2512.10371) |
| VeriSafe Agent: Safeguarding Mobile GUI Agent via Logic-based Action Verification | 2025.11 | MobiCom | [Paper](https://doi.org/10.1145/3680207.3765248) |
| Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment | 2025.10 | MobiCom | [Paper](https://arxiv.org/abs/2503.15937) |
| UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning | 2025.9 | arXiv | [Paper](https://arxiv.org/abs/2509.02544) |
| AutoDroid-V2: Boosting SLM-based GUI Agents via Code Generation | 2025.6 | MobiSys | [Paper](https://doi.org/10.1145/3711875.3729134) |
| ShowUI: One Vision-Language-Action Model for GUI Visual Agent | 2025.6 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Lin_ShowUI_One_Vision-Language-Action_Model_for_GUI_Visual_Agent_CVPR_2025_paper.html) |
| LLM-Explorer: Towards Efficient and Affordable LLM-based Exploration for Mobile Apps | 2025.5 | MobiCom | [Paper](https://arxiv.org/abs/2505.10593) |
| AutoDroid: LLM-powered Task Automation in Android | 2024.5 | MobiCom | [Paper](https://doi.org/10.1145/3636534.3649379) |

### 4. 端云与多设备协同

| 论文 | 日期 | 会议/期刊 | 链接 |
|---|---:|---|---|
| EcoAgent: An Efficient Device-Cloud Collaborative Multi-Agent Framework for Mobile Automation | 2026.4 | AAAI | [Paper](https://arxiv.org/abs/2505.05440) |
| OpenPhone: Mobile Agentic Foundation Models | 2025.10 | arXiv | [Paper](https://arxiv.org/abs/2510.22009) |
| Jupiter: Fast and Resource-Efficient Collaborative Inference of Generative LLMs on Edge Devices | 2025.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM55648.2025.11044734) |
| Federated Adaptive Fine-Tuning of Large Language Models with Heterogeneous Quantization and LoRA | 2025.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM55648.2025.11044641) |
| Towards Federated Inference: An Online Model Ensemble Framework for Cooperative Edge AI | 2025.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM55648.2025.11044578) |
| EdgeShard: Efficient LLM Inference via Collaborative Edge Computing | 2025.5 | JIOT | [Paper](https://doi.org/10.1109/JIOT.2024.3524255) |
| Galaxy: A Resource-Efficient Collaborative Edge AI System for In-situ Transformer Inference | 2024.5 | INFOCOM | [Paper](https://doi.org/10.1109/INFOCOM52122.2024.10621342) |

### 5. 数据集与基准

| 论文 | 日期 | 会议/期刊 | 链接 |
|---|---:|---|---|
| AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents | 2025.7 | ACL | [Paper](https://aclanthology.org/2025.acl-long.107/) |
| AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents | 2025.4 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/01a83bc2f2732a58e6aa731e659e7101-Abstract-Conference.html) |
| MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents | 2024.6 | arXiv | [Paper](https://arxiv.org/abs/2406.08184) |

### 6. 边缘智能（扩展阅读）

这些论文不是本仓库的主要目标，但有助于理解端侧智能体背后的效率、扩展规律和部署趋势。

| 论文 | 日期 | 会议/期刊 | 链接 |
|---|---:|---|---|
| Rethinking Scale: Deployment Trade-offs of Small Language Models under Agent Paradigms | 2026.4 | arXiv | [Paper](https://arxiv.org/abs/2604.19299) |
| An Information Theoretic Perspective on Agentic System Design | 2026.4 | ICLR | [Paper](https://arxiv.org/abs/2512.21720) |
| Densing law of LLMs | 2025.11 | Nature MI | [Paper](https://doi.org/10.1038/s42256-025-01137-0) |
| Intelligence per Watt: Measuring Intelligence Efficiency of Local AI | 2025.11 | arXiv | [Paper](https://arxiv.org/abs/2511.07885) |
| Small Language Models are the Future of Agentic AI | 2025.9 | arXiv | [Paper](https://arxiv.org/abs/2506.02153) |

## 开源系统

| 项目 | 关注点 | 平台 / 范围 | 链接 |
|---|---|---|---|
| llama.cpp | 常用的本地 LLM 推理运行时，支持 CPU/GPU 后端和广泛的模型生态 | 本地 LLM 推理 | [GitHub](https://github.com/ggml-org/llama.cpp) |
| MLC LLM | 面向原生应用、移动设备、浏览器和 GPU 的通用 LLM 部署引擎 | 跨平台 LLM 部署 | [GitHub](https://github.com/mlc-ai/mlc-llm) |
| ExecuTorch | PyTorch 端侧运行时，用于在移动、嵌入式和边缘设备上部署 AI 模型 | 端侧 AI 运行时 | [GitHub](https://github.com/pytorch/executorch) |
| MNN | 面向移动和边缘设备的轻量级深度学习推理引擎，支持 LLM 部署 | 移动和边缘推理 | [GitHub](https://github.com/alibaba/MNN) |
| OmniInfer | 跨平台本地 LLM/VLM 推理引擎，支持多后端和 OpenAI 兼容 API server | 跨设备本地推理 | [GitHub](https://github.com/omnimind-ai/OmniInfer) |
| Cactus | 面向移动设备和可穿戴设备的低时延 AI 引擎，支持多模态 API、ARM 优化和云端 fallback | 移动与可穿戴 AI | [GitHub](https://github.com/cactus-compute/cactus) |
| mLLM | 面向移动和边缘设备的快速轻量多模态 LLM 推理引擎，支持 Android、Jetson 和 QNN/NPU | 移动和边缘多模态推理 | [GitHub](https://github.com/UbiquitousLearning/mLLM) |
| Open-AutoGLM | 基于 VLM 屏幕理解、规划和 ADB 控制的手机智能体框架 | Android 手机智能体 | [GitHub](https://github.com/zai-org/Open-AutoGLM) |
| Mobile-Agent | 面向 GUI 任务自动化的开源移动设备操作智能体框架 | 移动 GUI 智能体 | [GitHub](https://github.com/X-PLUG/MobileAgent) |

## 说明

- 同一篇论文如果和多个主题相关，可能会出现在最合适的综合分类下。
- 对 arXiv 论文，如果能确认正式发表版本，会更新会议或期刊信息。
- 开源系统和论文分开列出，不视为经过同行评审的论文。
- 当前收录范围优先考虑 2024 年以来的近期工作。
- 当前索引以人工筛选过的论文为起点，后续扩展应保持谨慎，不追求无差别穷举。

## 贡献

欢迎贡献。请参阅 [CONTRIBUTING.md](CONTRIBUTING.md)。
