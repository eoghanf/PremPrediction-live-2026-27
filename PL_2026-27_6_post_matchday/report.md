# Matchday 6 Evaluation Report — 2026–27

## Leaderboard summary

**openrouter/x-ai/grok-4.5** led the matchday with a mean RPS of **0.2000**, ahead of **baseline/b4-dixonceoles** by **0.0025** and **openrouter/moonshotai/kimi-k3** by **0.0026**. Lower RPS is better.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | openrouter/x-ai/grok-4.5 | 0.2000 | 0.1709–0.2292 |
| 2 | baseline/b4-dixonceoles | 0.2025 | 0.1676–0.2390 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.2027 | 0.1719–0.2336 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.2078 | 0.1756–0.2415 |
| 5 | openrouter/z-ai/glm-5.2 | 0.2092 | 0.1750–0.2443 |
| 6 | openrouter/deepseek/deepseek-v4-flash | 0.2096 | 0.1775–0.2440 |
| 7 | openrouter/openai/gpt-5.6-terra | 0.2115 | 0.1776–0.2474 |
| 8 | baseline/b2-home | 0.2228 | 0.2043–0.2411 |
| 9 | baseline/b1-uniform | 0.2251 | 0.2056–0.2444 |
| 10 | baseline/b3-clubelo | 0.2255 | 0.2058–0.2460 |

All reported bootstrap intervals overlap substantially, including those of the leader and the bottom-ranked entrant. Therefore, the observed ordering—particularly among the leading group—should **not** be treated as a clearly meaningful separation on this matchday.

## Per-fixture outcomes and surprises

Ten fixtures have resolved outcomes in the supplied data:

| Fixture | Result | Outcome |
|---|---:|:---:|
| pl-128973 | 2–1 | H |
| pl-128974 | 2–2 | D |
| pl-128975 | 5–1 | H |
| pl-128979 | 2–1 | H |
| pl-128982 | 0–2 | A |
| pl-128981 | 1–1 | D |
| pl-128977 | 3–1 | H |
| pl-128978 | 2–2 | D |
| pl-128980 | 0–3 | A |
| pl-128976 | 4–1 | H |

The input does **not** include per-model, per-fixture RPS or probability forecasts. As a result, it does not support identifying which model was notably right or wrong on any individual fixture. The most emphatic scorelines among the resolved set were home wins in **pl-128975 (5–1)** and **pl-128976 (4–1)**, plus the away win in **pl-128980 (0–3)**, but no model-specific performance conclusion can be drawn from the provided data.

## Fallbacks and voids

| Fixture | Entrant | Issue |
|---|---|---|
| pl-128979 | openrouter/deepseek/deepseek-v4-flash | Missing prediction; fallback recorded and fixture voided |

**openrouter/deepseek/deepseek-v4-flash** had a missing submission for **pl-128979**, which was also listed as a void for that entrant. Its reported mean RPS was **0.2096** (sixth place). The data do not quantify the score or ranking effect of the fallback/void, so no numerical adjustment to its standing can be inferred.

## Market disagreement highlights

There were **no recorded biggest disagreements with the closing-market baseline**. Accordingly, there are no market-divergence calls to highlight for Matchday 6.