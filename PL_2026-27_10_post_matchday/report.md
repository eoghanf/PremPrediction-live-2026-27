# Matchday 10 Evaluation Report — 2026–27

## Leaderboard summary

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.2086 | 0.1846–0.2359 |
| 2 | openrouter/x-ai/grok-4.5 | 0.2122 | 0.1889–0.2365 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.2142 | 0.1900–0.2394 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.2148 | 0.1900–0.2411 |
| 5 | openrouter/z-ai/glm-5.2 | 0.2167 | 0.1902–0.2445 |
| 6 | openrouter/deepseek/deepseek-v4-flash | 0.2189 | 0.1924–0.2483 |
| 7 | openrouter/openai/gpt-5.6-terra | 0.2203 | 0.1937–0.2477 |
| 8 | baseline/b2-home | 0.2280 | 0.2142–0.2412 |
| 9 | baseline/b3-clubelo | 0.2290 | 0.2144–0.2438 |
| 10 | baseline/b1-uniform | 0.2326 | 0.2178–0.2461 |

**baseline/b4-dixonceoles led the matchday** with a mean RPS of **0.2086**, ahead of **Grok-4.5 by 0.0036**. Lower RPS is better.

However, the bootstrap intervals overlap substantially across the entire leaderboard—including between first and tenth—so the supplied uncertainty estimates do **not** support a clear meaningful separation between entrants on this matchday alone.

## Per-fixture outcomes and surprises

Ten fixtures have resolved scores in the supplied data:

| Fixture | Score | Outcome |
|---|---:|:---:|
| pl-129016 | 3–1 | H |
| pl-129019 | 1–0 | H |
| pl-129013 | 1–0 | H |
| pl-129017 | 1–1 | D |
| pl-129021 | 3–1 | H |
| pl-129014 | 2–0 | H |
| pl-129015 | 1–3 | A |
| pl-129018 | 1–2 | A |
| pl-129022 | 1–0 | H |
| pl-129020 | 4–4 | D |

The resolved set contained **six home wins, two away wins, and two draws**. The 4–4 draw in **pl-129020** was the highest-scoring result.

No entrant-level per-fixture RPS or forecast probabilities are included, so it is **not possible to identify which specific models were notably right or wrong** on individual fixtures from this evaluation extract. In addition, 20 listed fixtures have null scores and outcomes.

## Fallbacks and voids

Six model submissions were marked **missing** for **pl-129014**, and the same six entries were both listed as fallbacks and voids:

- openrouter/deepseek/deepseek-v4-flash  
- openrouter/openai/gpt-5.6-luna  
- openrouter/openai/gpt-5.6-terra  
- openrouter/x-ai/grok-4.5  
- openrouter/z-ai/glm-5.2  
- openrouter/moonshotai/kimi-k3  

This affected all six OpenRouter entrants, while the listed baselines were unaffected. The data does not provide the replacement forecasts, scoring treatment beyond the void status, or counterfactual scores, so the precise numerical effect on the standings cannot be quantified. It is nevertheless an important comparability caveat for the OpenRouter models’ matchday results.

## Market-disagreement highlights

There were **no recorded biggest disagreements with the closing-market baseline**. Accordingly, no market-divergence fixture or model can be highlighted from the supplied data.