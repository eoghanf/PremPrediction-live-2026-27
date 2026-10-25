# Matchday 8 Forecast Report — 2026–27 Season

## 1. Coverage verification

**Coverage is complete.** All 10 models produced a forecast for each of the 10 fixtures:

- `all_covered: true`
- **Missing rows:** none (`missing_rows: []`)
- **Fallback rows:** none reported
- Every listed prediction has `status: ok`
- Baseline models supplied **1 valid sample per fixture**; OpenRouter models supplied **3 valid samples per fixture**.

## 2. Forecast comparison

### Broad areas of agreement

Excluding the uniform baseline—which assigns 33.3% to every outcome—there is strong agreement on the likely winner in several fixtures:

| Fixture | Broad consensus |
|---|---|
| Ipswich Town vs Nottingham Forest | Ipswich home win; only Dixon–Coles prefers Forest |
| Aston Villa vs Manchester City | Manchester City away win among all six OpenRouter models and Dixon–Coles |
| Arsenal vs Everton | Arsenal home win across every non-uniform model |
| Coventry City vs Fulham | Coventry home win across all OpenRouter models; Dixon–Coles instead prefers Fulham |
| Chelsea vs Tottenham Hotspur | Chelsea home win across every non-uniform model |
| Hull City vs Brentford | Brentford away win across all six OpenRouter models |
| Sunderland vs Leeds United | Leeds away win across every non-uniform model |

Arsenal are the clearest home favourite in the compiled forecasts: `gpt-5.6-terra` assigns Arsenal a **64.7%** home-win probability, while `glm-5.2` assigns **64.5%** and `kimi-k3` **63.7%**.

Manchester City are the strongest away favourite: `glm-5.2` gives City a **63.0%** away-win probability and `kimi-k3` gives **62.7%**.

### Largest divergences

| Fixture | Main disagreement |
|---|---|
| Manchester United vs Bournemouth | `deepseek-v4-flash` makes Bournemouth the favourite (**49.2% away**), while every other non-uniform model favours Manchester United at home. |
| Ipswich Town vs Nottingham Forest | Dixon–Coles strongly prefers Nottingham Forest (**50.9% away**); all six OpenRouter models, plus the home and ClubElo baselines, prefer Ipswich. |
| Coventry City vs Fulham | Dixon–Coles selects Fulham (**43.7% away**), whereas all OpenRouter models favour Coventry. |
| Liverpool vs Brighton & Hove Albion | `deepseek-v4-flash` narrowly favours Brighton (**39.8% away**) over Liverpool (**31.5% home**); the other five OpenRouter models favour Liverpool. |
| Crystal Palace vs Newcastle United | The OpenRouter set is evenly split: DeepSeek, Terra, and GLM favour Palace; Kimi, Luna, and Grok favour Newcastle. |
| Hull City vs Brentford | All OpenRouter models favour Brentford, but the three non-uniform baseline models favour Hull at home. |

### Notable probabilities

- **Liverpool vs Brighton** is particularly uncertain: the non-uniform models’ top probabilities range from Brighton at **39.8%** (`deepseek-v4-flash`) to Liverpool at **48.2%** (`glm-5.2`).
- **Crystal Palace vs Newcastle** is also finely balanced. `grok-4.5` gives Newcastle **42.3%**, while `gpt-5.6-terra` gives Palace **40.1%**.
- **Sunderland vs Leeds** has consistent directional agreement on Leeds, but its draw estimates remain relatively elevated: Dixon–Coles assigns a **31.1%** draw probability and DeepSeek **31.0%**.
- Among non-uniform forecasts, the highest draw probability is Dixon–Coles’ **31.1%** for Sunderland vs Leeds.

## 3. Forecast-production cost

All provider-reported dollar costs are **$0.00**, despite recorded token usage of **987,695 tokens** overall.

| Model | Samples | Tokens | Spend (USD) |
|---|---:|---:|---:|
| `baseline/b1-uniform` | 10 | 0 | $0.00 |
| `baseline/b2-home` | 10 | 0 | $0.00 |
| `baseline/b3-clubelo` | 10 | 0 | $0.00 |
| `baseline/b4-dixonceoles` | 10 | 0 | $0.00 |
| `openrouter/deepseek/deepseek-v4-flash` | 30 | 377,060 | $0.00 |
| `openrouter/moonshotai/kimi-k3` | 30 | 133,737 | $0.00 |
| `openrouter/openai/gpt-5.6-luna` | 30 | 76,357 | $0.00 |
| `openrouter/openai/gpt-5.6-terra` | 30 | 25,782 | $0.00 |
| `openrouter/x-ai/grok-4.5` | 30 | 104,513 | $0.00 |
| `openrouter/z-ai/glm-5.2` | 30 | 270,246 | $0.00 |
| **Total** | **220** | **987,695** | **$0.00** |