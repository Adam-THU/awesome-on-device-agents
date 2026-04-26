# Open Problems

## 1. Mobile Agent Evaluation

Current GUI-agent benchmarks often simplify real mobile use. Open problems include:

- long-horizon task evaluation;
- robustness across apps, OS versions, and UI changes;
- measuring user trust and recoverability;
- evaluating failed or partially completed tasks.

## 2. On-device Capability under Resource Limits

Mobile devices are constrained by memory, energy, thermals, and latency.

Open questions:

- Which agent capabilities must be local?
- How small can a useful mobile agent model be?
- How should we measure intelligence per watt for agentic tasks?
- How do we balance model size, tool use, and retrieval?

## 3. Device-cloud Collaboration

Pure on-device inference can be too weak, while pure cloud inference can be expensive and privacy-sensitive.

Open questions:

- What is the right split between local and cloud agents?
- How should systems decide when to offload?
- What data should remain local?
- How should device-cloud collaboration be evaluated?

## 4. Safety and Verification

Mobile agents can perform destructive or privacy-sensitive actions.

Open questions:

- How can actions be verified before execution?
- How can users inspect and approve plans?
- How should agents recover after wrong actions?
- How can safety rules be represented on device?

## 5. Multimodal Mobile Agents

Mobile devices provide screen, camera, microphone, sensors, location, and personal data.

Open questions:

- How should these signals be unified into task context?
- Which modalities are worth processing locally?
- How should agents handle noisy sensor or UI observations?
- How can multimodal context be summarized efficiently?

## 6. Multi-agent Mobile Systems

Multiple devices can collaborate while preserving local data.

Open questions:

- What communication protocol is sufficient for edge agents?
- How should agents share summaries instead of raw data?
- How can systems handle unreliable devices or networks?
- How can collaborative agents be evaluated against single-agent baselines?

