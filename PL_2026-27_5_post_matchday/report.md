# Matchday 5 Evaluation Report — 2026–27

## Leaderboard summary

Lower mean RPS is better. **baseline/b4-dixonceoles** led Matchday 5 with a mean RPS of **0.1919**, ahead of **openrouter/x-ai/grok-4.5** by **0.0093**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.1919 | 0.1577–0.2303 |
| 2 | openrouter/x-ai/grok-4.5 | 0.2013 | 0.1708–0.2344 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.2048 | 0.1716–0.2393 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.2097 | 0.1752–0.2468 |
| 5 | openrouter/z-ai/glm-5.2 | 0.2129 | 0.1760–0.2530 |
| 6 | openrouter/deepseek/deepseek-v4-flash | 0.2143 | 0.1794–0.2522 |
| 7 | openrouter/openai/gpt-5.6-terra | 0.2161 | 0.1784–0.2574 |
| 8 | baseline/b2-home | 0.2240 | 0.2042–0.2446 |
| 9 | baseline/b1-uniform | 0.2246 | 0.2044–0.2444 |
| 10 | baseline/b3-clubelo | 0.2280 | 0.2073–0.2505 |

The leader’s interval overlaps with every other entrant’s interval, including the last-placed **baseline/b3-clubelo**. Therefore, the reported bootstrap intervals do **not** establish a clear meaningful separation between models for this matchday, despite the point-estimate ordering.

## Per-fixture observations

Ten fixtures have recorded outcomes:

- **Home wins:** pl-128964 (3–0), pl-128965 (3–0), pl-128966 (1–0), pl-128970 (2–1), pl-128969 (5–3)
- **Away wins:** pl-128972 (2–3), pl-128971 (0–1), pl-128963 (0–1)
- **Draws:** pl-128968 (0–0), pl-128967 (1–1)

However, no entrant-level per-fixture RPS or prediction data is supplied. As a result, the evaluation cannot identify which model was notably right or wrong on any individual fixture.

## Fallbacks and voids

- **Fallbacks:** none.
- **Voids:** none.

No fallback or void adjustment was reported, so there is no stated direct impact from either mechanism on the standings.

The fixture list nevertheless contains **20 entries with null outcomes and null scores**. They are not marked as voids in the supplied data, and their scoring treatment cannot be determined from this evaluation alone.

## Market-disagreement highlights

No biggest disagreements with the closing-market baseline were reported. Therefore, there are no market-disagreement fixtures or model calls to highlight for Matchday 5.