# Matchday 9 Evaluation — 2026–27

## Leaderboard summary

**openrouter/x-ai/grok-4.5** led the evaluated standings with a mean RPS of **0.2082**. It finished **0.0021 RPS** ahead of **baseline/b4-dixonceoles** (0.2103), with the next two entrants effectively tied around 0.2108.

| Rank | Entrant | Mean RPS | Bootstrap interval |
|---:|---|---:|---|
| 1 | openrouter/x-ai/grok-4.5 | 0.2082 | 0.1849–0.2321 |
| 2 | baseline/b4-dixonceoles | 0.2103 | 0.1838–0.2396 |
| 3 | openrouter/openai/gpt-5.6-luna | 0.2108 | 0.1862–0.2373 |
| 4 | openrouter/moonshotai/kimi-k3 | 0.2108 | 0.1863–0.2367 |
| 5 | openrouter/z-ai/glm-5.2 | 0.2137 | 0.1863–0.2420 |
| 6 | openrouter/deepseek/deepseek-v4-flash | 0.2151 | 0.1883–0.2431 |
| 7 | openrouter/openai/gpt-5.6-terra | 0.2169 | 0.1897–0.2455 |
| 8 | baseline/b2-home | 0.2285 | 0.2143–0.2427 |
| 9 | baseline/b3-clubelo | 0.2305 | 0.2152–0.2463 |
| 10 | baseline/b1-uniform | 0.2314 | 0.2148–0.2463 |

All bootstrap intervals overlap substantially, including between the leader and every other entrant. Therefore, the observed ordering—particularly among the top seven—should **not** be treated as a meaningful separation in performance on this evaluation.

## Per-fixture results and surprises

The supplied fixture data records results for **10 fixtures**:

| Fixture | Result | Outcome |
|---|---:|:---:|
| pl-129006 | 2–0 | H |
| pl-129004 | 2–0 | H |
| pl-129005 | 2–0 | H |
| pl-129007 | 3–1 | H |
| pl-129008 | 2–2 | D |
| pl-129010 | 0–1 | A |
| pl-129012 | 2–0 | H |
| pl-129003 | 1–1 | D |
| pl-129009 | 0–1 | A |
| pl-129011 | 0–1 | A |

This produced **five home wins, two draws, and three away wins**.

However, no entrant-level per-fixture RPS values or forecast probabilities are included in the supplied data. As a result, it is not possible to identify which models were notably right or wrong on individual fixtures, or to attribute the aggregate leaderboard differences to particular matches.

The remaining **20 listed fixtures** have null scores and outcomes in the data provided, so no fixture-level evaluation can be reported for them.

## Fallbacks and voids

- **Fallbacks:** none.
- **Voids:** none.

Accordingly, no entrant received a fallback forecast and no fixture was removed from scoring through a void. The standings therefore contain no stated adjustment from either mechanism.

## Market disagreement highlights

No biggest disagreements with the closing-market baseline were recorded. Therefore, there are **no market-disagreement fixtures or model calls to highlight** for this matchday.