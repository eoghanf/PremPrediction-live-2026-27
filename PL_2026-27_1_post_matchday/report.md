# Matchday 1 Evaluation — 2026–27

## Leaderboard summary

Lower mean RPS is better. **baseline/b4-dixonceoles** led Matchday 1 with a mean RPS of **0.1927**, ahead of **openrouter/moonshotai/kimi-k3** on **0.2127** — a margin of **0.0200**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.1927 | 0.1404–0.2398 |
| 2 | openrouter/moonshotai/kimi-k3 | 0.2127 | 0.1355–0.2919 |
| =3 | baseline/b2-home | 0.2223 | 0.1893–0.2643 |
| =3 | baseline/b3-clubelo | 0.2223 | 0.1893–0.2643 |
| 5 | openrouter/x-ai/grok-4.5 | 0.2234 | 0.1424–0.3088 |
| 6 | openrouter/openai/gpt-5.6-luna | 0.2270 | 0.1458–0.3140 |
| 7 | openrouter/z-ai/glm-5.2 | 0.2534 | 0.1446–0.3689 |
| 8 | openrouter/deepseek/deepseek-v4-flash | 0.2577 | 0.1640–0.3598 |
| 9 | openrouter/openai/gpt-5.6-terra | 0.2599 | 0.1484–0.3855 |
| 10 | baseline/b1-uniform | 0.2616 | 0.2278–0.2778 |

All reported bootstrap intervals overlap the leader’s interval. On this matchday alone, the point-estimate ordering does **not** establish a clear statistically separated advantage. The closest non-leader was Kimi K3; b2-home and b3-clubelo were tied exactly.

## Per-fixture outcomes and surprises

The supplied fixture data contains resolved outcomes for **10 fixtures**:

- **8 home wins**
- **1 draw**
- **1 away win**

| Fixture | Result | Outcome |
|---|---:|:---:|
| pl-128923 | 3–0 | H |
| pl-128926 | 2–0 | H |
| pl-128925 | 2–0 | H |
| pl-128927 | 2–1 | H |
| pl-128928 | 0–1 | A |
| pl-128924 | 3–0 | H |
| pl-128929 | 4–0 | H |
| pl-128930 | 2–1 | H |
| pl-128931 | 2–2 | D |
| pl-128932 | 2–3 | A |

No entrant-level per-fixture RPS or forecasts are included. Therefore, the evaluation cannot identify which specific model was notably right or wrong on any individual fixture. The available fixture data does show a strongly home-win-heavy set of resolved results, with only pl-128928 and pl-128932 ending in away wins and pl-128931 drawn.

## Fallbacks and voids

- **Fallbacks:** None.
- **Voids:** None.

Accordingly, no standings adjustment was required from fallback or void handling.

The dataset also lists 20 fixtures with null score and outcome fields. They are not labelled as voids or fallbacks, so no impact on the published standings can be inferred from them.

## Market-disagreement highlights

No biggest disagreements with the closing-market baseline were recorded. There are therefore no market-divergence fixtures or model calls to highlight for Matchday 1.