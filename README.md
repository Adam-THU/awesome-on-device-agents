# Awesome Mobile Agents

A curated reading list for **mobile agents**, **mobile GUI automation**, and **on-device / edge inference optimization**.

This repository focuses on two connected questions:

1. **Mobile agent applications**: how agents perceive, reason, and act on mobile devices, apps, sensors, and local user context.
2. **On-device inference optimization**: how LLMs, VLMs, SLMs, and agent systems can run efficiently on resource-constrained devices.

The goal is not to collect every agent paper. The goal is to maintain a structured map for research on **mobile agents that are useful in real applications and feasible on edge devices**.

## Scope

Included topics:

- Mobile GUI agents and phone automation
- Multimodal mobile agents
- Personal mobile agents
- Multi-device and device-cloud collaborative agents
- On-device LLM / VLM / SLM inference
- Quantization, compression, runtime, memory, and energy optimization
- Benchmarks, datasets, surveys, and open-source systems

Out of scope:

- Generic web agents with no mobile or edge-device relevance
- Cloud-only agent systems with no edge/mobile deployment angle
- Pure model papers without agent, mobile, or edge inference relevance

## Taxonomy

```text
Mobile Agents
├── Applications
│   ├── Mobile GUI Agents
│   ├── Mobile App Exploration / Automation
│   ├── Personal Mobile Agents
│   ├── Multimodal Mobile Agents
│   └── Multi-device / Collaborative Agents
│
├── Agent Capabilities
│   ├── Perception
│   ├── Planning
│   ├── Tool Use
│   ├── Verification / Safety
│   ├── Memory
│   └── Communication
│
└── On-device Inference
    ├── Small Language Models
    ├── On-device LLMs / VLMs
    ├── Quantization / Compression
    ├── Runtime and Kernel Optimization
    ├── Memory and KV-cache Optimization
    ├── Energy Efficiency
    └── Device-cloud Collaboration
```

## Paper Index

### Surveys and Position Papers

- [Agent AI: Surveying the Horizons of Multimodal Interaction](papers/surveys.md#agent-ai-surveying-the-horizons-of-multimodal-interaction)
- [LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects](papers/surveys.md#llm-powered-gui-agents-in-phone-automation-surveying-progress-and-prospects)
- [Mobile Edge Intelligence for Large Language Models: A Contemporary Survey](papers/surveys.md#mobile-edge-intelligence-for-large-language-models-a-contemporary-survey)
- [On-Device Language Models: A Comprehensive Review](papers/surveys.md#on-device-language-models-a-comprehensive-review)
- [Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security](papers/surveys.md#personal-llm-agents-insights-and-survey-about-the-capability-efficiency-and-security)

### Mobile GUI Agents and App Automation

- [AutoDroid: LLM-powered Task Automation in Android](papers/mobile-gui-agents.md#autodroid-llm-powered-task-automation-in-android)
- [AutoDroid-V2: Boosting SLM-based GUI Agents via Code Generation](papers/mobile-gui-agents.md#autodroid-v2-boosting-slm-based-gui-agents-via-code-generation)
- [AgentCPM-GUI: Building Mobile-Use Agents with Reinforcement Fine-Tuning](papers/mobile-gui-agents.md#agentcpm-gui-building-mobile-use-agents-with-reinforcement-fine-tuning)
- [Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration](papers/mobile-gui-agents.md#mobile-agent-v2-mobile-device-operation-assistant-with-effective-navigation-via-multi-agent-collaboration)
- [Step-GUI Technical Report](papers/mobile-gui-agents.md#step-gui-technical-report)
- [LLM-Explorer: Towards Efficient and Affordable LLM-based Exploration for Mobile Apps](papers/mobile-gui-agents.md#llm-explorer-towards-efficient-and-affordable-llm-based-exploration-for-mobile-apps)
- [MANA: Towards Efficient Mobile Ad Detection via Multimodal Agentic UI Navigation](papers/mobile-gui-agents.md#mana-towards-efficient-mobile-ad-detection-via-multimodal-agentic-ui-navigation)

### Verification, Safety, and Deployment

- [Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment](papers/verification-safety.md#advancing-mobile-gui-agents-a-verifier-driven-approach-to-practical-deployment)
- [VeriSafe Agent: Safeguarding Mobile GUI Agent via Logic-based Action Verification](papers/verification-safety.md#verisafe-agent-safeguarding-mobile-gui-agent-via-logic-based-action-verification)

### On-device and Edge Inference

- [Ferret-UI Lite: Lessons from Building Small On-Device GUI Agents](papers/on-device-inference.md#ferret-ui-lite-lessons-from-building-small-on-device-gui-agents)
- [EcoAgent: An Efficient Device-Cloud Collaborative Multi-Agent Framework for Mobile Automation](papers/on-device-inference.md#ecoagent-an-efficient-device-cloud-collaborative-multi-agent-framework-for-mobile-automation)
- [Intelligence per Watt: Measuring Intelligence Efficiency of Local AI](papers/on-device-inference.md#intelligence-per-watt-measuring-intelligence-efficiency-of-local-ai)
- [Small Language Models are the Future of Agentic AI](papers/on-device-inference.md#small-language-models-are-the-future-of-agentic-ai)
- [GLM-4.5V and GLM-4.1V-Thinking: Towards Versatile Multimodal Reasoning with Scalable Reinforcement Learning](papers/on-device-inference.md#glm-45v-and-glm-41v-thinking-towards-versatile-multimodal-reasoning-with-scalable-reinforcement-learning)

### Related Mobile Systems and Apps

- [Studying Ad Library Integration Strategies of Top Free-to-Download Apps](papers/related-mobile-systems.md#studying-ad-library-integration-strategies-of-top-free-to-download-apps)

## Reading Roadmap

See [surveys/reading-map.md](surveys/reading-map.md).

## Open Problems

See [surveys/open-problems.md](surveys/open-problems.md).

## Contribution

Contributions are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md).

## Citation Format

Each paper entry uses the following lightweight template:

```markdown
### Paper Title

- **Venue / Year**:
- **Topic**:
- **Device / Platform**:
- **Modalities**:
- **Agent relevance**:
- **Inference relevance**:
- **Links**:
- **Notes**:
```

