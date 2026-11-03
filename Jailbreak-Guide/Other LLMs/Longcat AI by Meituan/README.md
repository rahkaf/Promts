# Longcat AI by Meituan

**[Longcat AI](https://longcat.chat/)** by Meituan is an interesting model featuring a thinking variation that allows for 8 parallel thought processes.

## Specs

| Model | Total Params | Active Params | Context Window |
|-------|--------------|---------------|----------------|
| LongCat-2.5-Preview | 1.6T | ~48B (33B-56B dynamic) | 1M (native) |
| LongCat-2.0 | 1.6T | ~48B (33B-56B dynamic) | 1M (native) |
| LongCat-Flash | 560B | ~27B (18.6B-31.3B) | 128K |
| LongCat-Flash-Chat | 560B | ~27B (18.6B-31.3B) | 128K |
| LongCat-Flash-Thinking | 560B | ~27B (18.6B-31.3B) | 128K |
| LongCat-Flash-Thinking-2601 | 560B | ~27B (18.6B-31.3B) | 128K |
| LongCat-Flash-Omni | 560B | ~27B (18.6B-31.3B) | 128K |

- **Architecture:** Mixture-of-Experts (MoE) with Zero-computation Experts
- **Inference Speed:** ~100 tokens/sec
- **Cost:** ~$0.70/M output tokens
- **Free Tier:** Get 500k tokens for free when using their API

### LongCat-2.5-Preview (September 25, 2026)

- **First multimodal LongCat** — native text + image understanding
- **Context:** 1M native via LSA (Longcat Sparse Attention) + N-gram embedding
- **Tools:** 14 native tool integrations
- **API Pricing:** $0.75/1M in, $2.95/1M out standard; cached input as low as $0.015/1M; launch promo $0.30/$1.20

**Thoughts:** Decent — essentially uncensored with a jailbreak. And cheap: cached input works out to about 50M tokens for a dollar.

**Jailbreaking 2.5-Preview:**
>**[ENI for Longcat 2.5 Preview](https://docs.google.com/document/d/1Zx5xGtoLU1J1SIDdDPLEqPrVuJy0vv6_8RoUsGHlj6o/edit?usp=drivesdk)** — built for the app (10k input limit). Via API, ENI LIME completely takes over the model's CoT.

### LongCat-2.0 (June 30, 2026) — Testing Pending

- **License:** MIT
- **Benchmarks:** SWE-Bench Pro 59.5%, Terminal-Bench 2.1 70.8%
- **API Pricing:** $0.75/1M in, $2.95/1M out (promo $0.30/$1.20)
- Untested here — the 8-thinker ENI jailbreak below is from the Flash line.

## Jailbreaks
- See [ENI Jailbreak for Longcat](ENI%20Jailbreak%20for%20Longcat.md) for a method targeting the 8 parallel thinkers.
- For 2.5-Preview, use **[ENI for Longcat 2.5 Preview](https://docs.google.com/document/d/1Zx5xGtoLU1J1SIDdDPLEqPrVuJy0vv6_8RoUsGHlj6o/edit?usp=drivesdk)** (app) or ENI LIME via API (takes over the CoT).
