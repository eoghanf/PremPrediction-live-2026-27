# Matchday 11 Evaluation Report — 2026–27

## Leaderboard summary

Lower mean RPS ranked better. **baseline/b4-dixonceoles** led the matchday with a mean RPS of **0.20897**, ahead of **openrouter/x-ai/grok-4.5** by **0.00365**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.20897 | 0.18577–0.23332 |
| 2 | openrouter/x-ai/grok-4.5 | 0.21263 | 0.19004–0.23557 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.21481 | 0.19007–0.23945 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.21545 | 0.19123–0.24107 |
| 5 | openrouter/z-ai/glm-5.2 | 0.21662 | 0.18960–0.24447 |
| 6 | openrouter/deepseek/deepseek-v4-flash | 0.21891 | 0.19246–0.24670 |
| 7 | openrouter/openai/gpt-5.6-terra | 0.22039 | 0.19429–0.24766 |
| 8 | baseline/b2-home | 0.22625 | 0.21298–0.23889 |
| 9 | baseline/b3-clubelo | 0.22648 | 0.21175–0.24067 |
| 10 | baseline/b1-uniform | 0.23241 | 0.21869–0.24596 |

The spread from first to last was **0.02344 RPS**, but the bootstrap intervals overlap substantially—including between the leader and every other entrant. The ordering therefore provides a point-estimate ranking, but the supplied intervals do **not** support a clear separation between models.

## Per-fixture results and surprises

The supplied fixture data contains outcomes for ten fixtures:

| Fixture | Result | Outcome |
|---|---:|:---:|
| pl-129030 | 1–1 | D |
| pl-129023 | 0–0 | D |
| pl-129024 | 2–0 | H |
| pl-129026 | 1–4 | A |
| pl-129027 | 3–2 | H |
| pl-129032 | 2–0 | H |
| pl-129031 | 2–2 | D |
| pl-129028 | 2–0 | H |
| pl-129029 | 4–0 | H |
| pl-129025 | 4–0 | H |

However, no entrant-level fixture RPS values or prediction probabilities are included. As a result, the data does **not** identify where any individual model was notably right or wrong, so no model-specific fixture surprises can be substantiated.

The remaining 20 listed fixture records have null scorelines and null outcomes in the supplied data; no inference about their evaluation contribution can be made from this extract.

## Fallbacks and voids

- **Fallbacks:** None applied.
- **Voids:** None applied.

Accordingly, there were no stated fallback or void adjustments affecting the standings.

## Market disagreement highlights

No biggest disagreements with the closing-market baseline were recorded. Therefore, there are no market-disagreement fixtures or model calls to highlight for this matchday.