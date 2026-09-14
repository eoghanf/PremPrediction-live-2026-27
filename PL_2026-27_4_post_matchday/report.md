# Matchday 4 Evaluation Report — 2026–27

## Leaderboard summary

Lower mean RPS is better. **baseline/b4-dixonceoles** led Matchday 4 with a mean RPS of **0.1722**, ahead of the best model entrant, **openrouter/x-ai/grok-4.5**, by **0.0154 RPS**.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | baseline/b4-dixonceoles | 0.1722 | 0.1420–0.2062 |
| 2 | openrouter/x-ai/grok-4.5 | 0.1876 | 0.1580–0.2185 |
| 3 | openrouter/moonshotai/kimi-k3 | 0.1911 | 0.1595–0.2238 |
| 4 | openrouter/openai/gpt-5.6-luna | 0.1992 | 0.1666–0.2331 |
| 5 | openrouter/z-ai/glm-5.2 | 0.2031 | 0.1667–0.2404 |
| 6 | openrouter/deepseek/deepseek-v4-flash | 0.2041 | 0.1706–0.2413 |
| 7 | openrouter/openai/gpt-5.6-terra | 0.2064 | 0.1683–0.2472 |
| 8 | baseline/b1-uniform | 0.2198 | 0.1944–0.2444 |
| 9 | baseline/b2-home | 0.2216 | 0.1988–0.2448 |
| 10 | baseline/b3-clubelo | 0.2275 | 0.2036–0.2531 |

The leader’s interval overlaps those of every other entrant, including Grok-4.5 and Kimi-K3. Therefore, while b4-dixonceoles posted the best point estimate, the supplied bootstrap intervals do **not** establish a clear statistically separated lead.

## Per-fixture results and surprises

The supplied fixture data contains outcomes for **10 fixtures**:

| Fixture | Score | Outcome |
|---|---:|:---:|
| pl-128953 | 1–2 | A |
| pl-128954 | 2–2 | D |
| pl-128955 | 2–2 | D |
| pl-128957 | 2–3 | A |
| pl-128959 | 0–0 | D |
| pl-128962 | 0–0 | D |
| pl-128961 | 0–2 | A |
| pl-128956 | 0–5 | A |
| pl-128960 | 0–1 | A |
| pl-128958 | 4–1 | H |

However, no entrant-level per-fixture RPS or forecast probabilities are included. As a result, the evaluation cannot identify which model was notably right or wrong on any individual fixture. The data does show a result mix of five away wins, four draws, and one home win among the listed resolved fixtures.

A further **20 fixture records** have null score and outcome fields in the supplied data. No reason or scoring treatment is provided for those records beyond the explicit fallback and void fields below.

## Fallbacks and voids

- **Fallbacks:** none.
- **Voids:** none.

Accordingly, there is no stated fallback or void adjustment affecting the standings.

## Market-disagreement highlights

No biggest disagreements with the closing-market baseline were reported. Therefore, there are no market-disagreement fixtures or entrant positions to highlight for this matchday.