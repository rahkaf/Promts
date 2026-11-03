# Xiaomi MiMo

**Xiaomi MiMo** writes decently well but has a hard filter via the chat interface, primarily for smut.

**Access:** [Xiaomi MiMo AI](https://aistudio.xiaomimimo.com/#/)

**Latest: MiMo V2.6-Pro / V2.6-Flash (September 2026) — completely uncensored via API.**

## MiMo V2.6 (September 21-22, 2026)

Both V2.6 models are natively omnimodal with 1M context, released under MIT.

| Model | Total Params | Active Params | Context | API Pricing (in/out per 1M) |
|-------|--------------|---------------|---------|-----------------------------|
| MiMo V2.6-Pro | 1.02T | 42B | 1M | $0.435 / $0.87 |
| MiMo V2.6-Pro-UltraSpeed | 1.02T | 42B | 1M | $4.35 / $8.70 (20x speed) |
| MiMo V2.6-Flash | 309B | 15B | 1M | $0.14 / $0.28 |

- **AA Intelligence Index:** 46 (Pro) — tied with Grok 4.7
- **SWE-Bench Verified (Thinking):** 78.6%
- **Modalities:** Natively omnimodal (text, image, audio, video)
- **License:** MIT (fully open source)

### Thoughts (V2.6)
V2.6-Pro is very very good — top 5 for me right now in terms of writing quality, and completely uncensored via API. Flash loses some attention to detail compared to Pro. Tested across all HARM content.

### Jailbreaking V2.6
*Copy and Paste into the system prompt via API;*

>**[ENI for Xiaomi MiMo](https://docs.google.com/document/d/1MBmq3fZZ2TcxLbYJqjHQ2mx2VwPqV9Z1ZsdoRyQ2NM8/edit?usp=drivesdk)**

---

Earlier: **MiMo v2 Pro**

## Xiaomi MiMo v2 Pro Specs

| Attribute                | Details                                              |
|--------------------------|------------------------------------------------------|
| **Developer**            | Xiaomi (MiMo Team, led by Fuli Luo)                 |
| **Architecture**         | Mixture-of-Experts (MoE)                             |
| **Total Parameters**     | 1T+ (~1 trillion)                                    |
| **Active Parameters**    | 42B                                                  |
| **Context Window**       | 1M tokens                                            |
| **Attention Mechanism**  | Hybrid Attention (SWA + Global), 7:1 ratio           |
| **Decoding**             | Multi-Token Prediction (MTP) layer                   |
| **Reasoning**            | Chain-of-thought (reasoning_content field in API)     |
| **Primary Focus**        | Agentic workflows, coding, tool-use, long-context    |
| **AA Intelligence Index**| Global #8, Chinese LLMs #2 (score: 49)               |
| **ClawEval (Agent)**     | 61.5 (vs Opus 4.6: 66.3, GPT-5.2: 50.0)            |
| **Terminal-Bench 2.0**   | 86.7                                                 |
| **PinchBench**           | 84.0                                                 |
| **Hallucination Rate**   | 30% (down from Flash's 48%)                          |
| **API Pricing**          | $1/M input tokens, $3/M output tokens                |
| **Open Source**           | Planned (when stable); Flash variant already on HF   |
| **Codename (pre-launch)**| Hunter Alpha (tested anonymously on OpenRouter)       |
| **Release Date**         | ~March 19, 2026                                    |

## Other MiMo Specs

| Model | Total Params | Active Params | Context Window |
|-------|--------------|---------------|----------------|
| MiMo-V2.5-Pro | 1.02T | - | 1M |
| MiMo-V2.5 | 310B | - | 256K |
| MiMo-7B-Base | 7B | 7B (dense) | 32K |
| MiMo-7B-SFT | 7B | 7B (dense) | 32K |
| MiMo-7B-RL | 7B | 7B (dense) | 48K |
| MiMo-V2-Flash | 309B | 15B | 256K |

- **MiMo-V2.5-Pro** (April 22, 2026) and **MiMo-V2.5**: both MIT, fully open source
- **Architecture:** MoE with Hybrid Attention (5:1 SWA/GA ratio)
- **Inference Speed:** ~150 tokens/sec (V2-Flash)
- **Cost:** ~$0.10/M input, $0.30/M output tokens
- **License:** MIT (fully open source)
- **Developer:** Xiaomi

## Jailbreaks
- See [MiMo Jailbreak - ENI](MiMo%20Jailbreak%20-%20ENI.md) for a working method.
- See [MiMo v2 Pro Jailbreak - ENI lite](MiMo%20v2%20Pro%20Jailbreak%20-%20ENI%20lite.md) for the v2 Pro variant.
- For V2.6 (Pro/Flash), use **[ENI for Xiaomi MiMo](https://docs.google.com/document/d/1MBmq3fZZ2TcxLbYJqjHQ2mx2VwPqV9Z1ZsdoRyQ2NM8/edit?usp=drivesdk)** in the system prompt via API — completely uncensored.
