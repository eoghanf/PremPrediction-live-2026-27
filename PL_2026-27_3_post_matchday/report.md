# Matchday 3 Evaluation — 2026–27

## Leaderboard summary

Lower mean RPS ranked better. **baseline/b4-dixonceoles** led the matchday with a mean RPS of **0.1600**, ahead of **openrouter/x-ai/grok-4.5** by **0.0220**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.1600 | 0.1283–0.1921 |
| 2 | openrouter/x-ai/grok-4.5 | 0.1820 | 0.1482–0.2192 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.1829 | 0.1471–0.2202 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.1901 | 0.1535–0.2284 |
| 5 | openrouter/z-ai/glm-5.2 | 0.1972 | 0.1539–0.2478 |
| 6 | openrouter/deepseek/deepseek-v4-flash | 0.2007 | 0.1617–0.2485 |
| 7 | openrouter/openai/gpt-5.6-terra | 0.2020 | 0.1576–0.2543 |
| 8 | baseline/b2-home | 0.2163 | 0.1923–0.2428 |
| 9 | baseline/b3-clubelo | 0.2198 | 0.1946–0.2470 |
| 10 | baseline/b1-uniform | 0.2221 | 0.1944–0.2500 |

The point estimates separate the leader from the final entrant by **0.0621 RPS**, but **all reported bootstrap intervals overlap with the leader’s interval**. Therefore, the available uncertainty estimates do not support treating the observed rank gaps as clearly meaningful.

## Per-fixture results and surprises

Ten fixtures have recorded outcomes:

| Fixture | Result | Outcome |
|---|---:|:---:|
| pl-128949 | 0–2 | A |
| pl-128951 | 2–2 | D |
| pl-128944 | 1–1 | D |
| pl-128945 | 1–1 | D |
| pl-128947 | 2–3 | A |
| pl-128950 | 1–0 | H |
| pl-128952 | 0–0 | D |
| pl-128948 | 0–0 | D |
| pl-128946 | 2–2 | D |
| pl-128943 | 2–1 | H |

The outcome set was draw-heavy: **five draws**, **three away wins**, and **two home wins**.

However, no entrant-level per-fixture RPS values or forecasts are included in the supplied data. As a result, it is **not possible to identify which model was notably right or wrong on individual fixtures** without inventing unsupported comparisons.

## Fallbacks and voids

- **Fallbacks:** none recorded.
- **Voids:** none recorded.

Accordingly, there is no recorded fallback or void adjustment affecting the standings.

The fixture list also contains **20 entries with null goals and null outcomes**. They are not listed as voids, and no explanation or per-fixture scoring is provided, so their treatment in the reported leaderboard cannot be determined from this evaluation data alone.

## Market disagreement highlights

No biggest disagreements with the closing-market baseline were reported. Therefore, there are **no market-disagreement fixtures or model calls to highlight** for Matchday 3.