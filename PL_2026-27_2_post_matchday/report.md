# Matchday 2 Evaluation Report — 2026–27

## Leaderboard summary

Lower mean RPS is better. **baseline/b4-dixonceoles** led the matchday with a mean RPS of **0.1676**, ahead of **openrouter/x-ai/grok-4.5** by **0.0307**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.1676 | 0.1294–0.2019 |
| 2 | openrouter/x-ai/grok-4.5 | 0.1983 | 0.1543–0.2477 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.1991 | 0.1558–0.2478 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.2056 | 0.1606–0.2551 |
| 5 | openrouter/deepseek/deepseek-v4-flash | 0.2146 | 0.1616–0.2743 |
| 6 | openrouter/openai/gpt-5.6-terra | 0.2188 | 0.1588–0.2874 |
| 7 | openrouter/z-ai/glm-5.2 | 0.2189 | 0.1594–0.2857 |
| 8 | baseline/b2-home | 0.2291 | 0.1991–0.2610 |
| 9 | baseline/b3-clubelo | 0.2315 | 0.2003–0.2643 |
| 10 | baseline/b1-uniform | 0.2449 | 0.2111–0.2694 |

**Interpretation:** The leader’s interval overlaps those of the runners-up through **baseline/b3-clubelo**, so the apparent advantage over most of the field is not clearly decisive on these bootstrap intervals alone. The leader’s interval does **not** overlap with **baseline/b1-uniform**’s interval, indicating clearer separation from the uniform baseline.

The second- and third-placed entrants were effectively level on point estimate: Grok-4.5 led Kimi-K3 by just **0.0008** mean RPS.

## Per-fixture outcomes and surprises

Ten fixture outcomes are present in the evaluation data:

| Fixture | Result | Outcome |
|---|---:|:---:|
| pl-128937 | 1–4 | A |
| pl-128939 | 2–2 | D |
| pl-128934 | 1–1 | D |
| pl-128936 | 0–1 | A |
| pl-128942 | 0–2 | A |
| pl-128935 | 4–3 | H |
| pl-128938 | 1–1 | D |
| pl-128941 | 1–0 | H |
| pl-128940 | 5–2 | H |
| pl-128933 | 0–1 | A |

The resolved outcomes were evenly mixed: **four away wins, three draws, and three home wins**.

However, the supplied data does **not** include entrant-level per-fixture RPS or prediction probabilities. It is therefore not possible to identify specific fixtures where an individual model was notably right or wrong without inventing evidence. The remaining listed fixtures have null result fields, and no outcome-based assessment can be made for them from this extract.

## Fallbacks and voids

- **Fallbacks applied:** none.
- **Voids applied:** none.

Accordingly, there was **no stated adjustment to the standings** from fallbacks or void handling.

## Market-disagreement highlights

No biggest disagreements with the closing-market baseline were recorded. Therefore, this matchday provides **no flagged model-versus-market disagreement cases** to highlight.