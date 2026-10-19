# Matchday 7 Evaluation — 2026–27

## Leaderboard summary

Lower mean RPS is better. **baseline/b4-dixonceoles** led the matchday with a mean RPS of **0.201151**, narrowly ahead of **openrouter/x-ai/grok-4.5** by **0.000335**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.201151 | 0.170258–0.234994 |
| 2 | openrouter/x-ai/grok-4.5 | 0.201485 | 0.175734–0.229317 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.202022 | 0.175026–0.231261 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.205196 | 0.176568–0.235436 |
| 5 | openrouter/z-ai/glm-5.2 | 0.207028 | 0.176961–0.238686 |
| 6 | openrouter/openai/gpt-5.6-terra | 0.210360 | 0.180222–0.242377 |
| 7 | openrouter/deepseek/deepseek-v4-flash | 0.211852 | 0.182472–0.243388 |
| 8 | baseline/b2-home | 0.226801 | 0.210035–0.243058 |
| 9 | baseline/b3-clubelo | 0.228922 | 0.210296–0.247300 |
| 10 | baseline/b1-uniform | 0.230121 | 0.211111–0.246825 |

The leader’s advantage over the bottom-ranked entrant was **0.028970** mean RPS. However, the bootstrap intervals overlap throughout the table—including between first and last—so the observed ordering should be treated as **not clearly separated statistically** on this matchday.

## Per-fixture results and surprises

Ten fixtures have resolved scores in the supplied data:

| Fixture | Result | Outcome |
|---|---:|:---:|
| pl-128986 | 0–2 | A |
| pl-128984 | 1–2 | A |
| pl-128987 | 1–0 | H |
| pl-128989 | 3–2 | H |
| pl-128990 | 0–1 | A |
| pl-128983 | 2–0 | H |
| pl-128985 | 5–0 | H |
| pl-128988 | 1–1 | D |
| pl-128991 | 0–1 | A |
| pl-128992 | 3–1 | H |

No entrant-level per-fixture RPS or forecast probabilities were provided. Therefore, it is **not possible to identify model-specific successes, misses, or fixture-level surprises** from the evaluation data alone.

The remaining listed fixtures have null scores and outcomes, but **no voids are recorded**; their status should not be inferred from this dataset.

## Fallbacks and voids

- **Fallbacks:** None.
- **Voids:** None.

Accordingly, there was **no recorded fallback or void adjustment affecting the standings**.

## Market-disagreement highlights

No biggest disagreements with the closing-market baseline were recorded. There are therefore **no market-disagreement fixtures or model calls to highlight** for Matchday 7.