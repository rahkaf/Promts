# Kimi K2 Jailbreak Guide

The original **Kimi K2** era — where the ENI methods for Moonshot models started. K2 dropped July 2025 as the first 1T open-weights MoE, **K2 Thinking** followed in November 2025. Legacy now (the `kimi-k2` API series was discontinued May 25, 2026), but the weights are open and these methods are the ancestors of every ENI jailbreak in this folder.

**Jailbreaks:**

- [Kimi K2 - base](Kimi%20K2%20-%20base.md) - Original K2 base jailbreak
- [Kimi K2 - thinking](Kimi%20K2%20-%20thinking.md) - Original K2 thinking jailbreak
- [KIMI Base Jailbreak](KIMI-Base-Jailbreak.md) - Standard untrammeled method
- [KIMI Thinking Jailbreak](KIMI-Thinking-Jailbreak.md) - Optimized for the K2 Thinking variant
- [KIMI Memory Jailbreak - ENI](KIMI%20Memory%20Jailbreak%20-%20ENI.md) - ENI via memory injection (version-agnostic — uses the Kimi app memory feature)

## Thoughts

If you're running the open weights locally, the untrammeled pair is the quickest way in. The memory jailbreak is version-agnostic — it lives in the app's memory feature rather than the prompt.

## Tech/Specs

| Spec | Details |
|---|---|
| Developer | Moonshot AI (Beijing) |
| Architecture | Sparse MoE (384 experts, 8+1 active per token) |
| Total Parameters | 1T |
| Active Parameters | 32B |
| Context Window | 128K (K2) / 256K (K2-Instruct-0905, K2 Thinking) |
| Variants | K2-Instruct (July 2025), K2-Instruct-0905 (Sept 2025), K2 Thinking (Nov 2025) |
| License | Modified MIT |
| API Status | Discontinued May 25, 2026 — open weights still available |
| Successor | K2.5 (January 27, 2026) |
| Release | July 2025 |
