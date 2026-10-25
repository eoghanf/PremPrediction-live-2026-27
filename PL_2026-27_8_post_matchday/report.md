# Matchday 8 Evaluation — 2026–27 Season

## Leaderboard summary

Lower mean RPS is better. **baseline/b4-dixonceoles** led Matchday 8 with a mean RPS of **0.2057**, narrowly ahead of **openrouter/x-ai/grok-4.5** by **0.0012**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.2057 | 0.1773–0.2382 |
| 2 | openrouter/x-ai/grok-4.5 | 0.2069 | 0.1823–0.2326 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.2107 | 0.1846–0.2389 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.2112 | 0.1856–0.2389 |
| 5 | openrouter/z-ai/glm-5.2 | 0.2138 | 0.1855–0.2444 |
| 6 | openrouter/openai/gpt-5.6-terra | 0.2176 | 0.1886–0.2483 |
| 7 | openrouter/deepseek/deepseek-v4-flash | 0.2184 | 0.1903–0.2493 |
| 8 | baseline/b2-home | 0.2279 | 0.2127–0.2432 |
| 9 | baseline/b1-uniform | 0.2299 | 0.2132–0.2465 |
| 10 | baseline/b3-clubelo | 0.2305 | 0.2142–0.2476 |

All bootstrap intervals overlap substantially, including those of the leader and the bottom three entrants. Therefore, the observed ordering—especially the **0.0012** gap between first and second—does **not** provide clear evidence of a meaningful performance difference on this matchday.

## Per-fixture outcomes and surprises

Ten fixtures have resolved outcomes in the supplied data:

| Fixture | Score | Outcome |
|---|---:|:---:|
| pl-128999 | 1–1 | D |
| pl-128994 | 2–1 | H |
| pl-128993 | 2–0 | H |
| pl-128996 | 0–1 | A |
| pl-128995 | 0–2 | A |
| pl-129000 | 2–0 | H |
| pl-128997 | 0–2 | A |
| pl-128998 | 1–1 | D |
| pl-129001 | 0–3 | A |
| pl-129002 | 0–0 | D |

No entrant-level per-fixture RPS or prediction probabilities were provided. As a result, the data does not support identifying which models were notably right or wrong on individual fixtures, or classifying any result as a forecast surprise.

The remaining listed fixtures have null scores and outcomes in the supplied evaluation data; no separate void designation is attached to them.

## Fallbacks and voids

- **Fallbacks:** none.
- **Voids:** none.

Accordingly, there was **no recorded fallback or void adjustment** affecting the leaderboard.

## Market disagreement highlights

No biggest disagreements with the closing-market baseline were recorded. Therefore, there are no market-disagreement fixtures to highlight for Matchday 8.