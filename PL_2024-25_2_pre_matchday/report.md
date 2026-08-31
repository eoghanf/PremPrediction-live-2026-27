# Matchday 2 Forecast Report — 2026–27 Season

## Coverage verification

**Coverage is complete.** All **10 models** produced a forecast for each of the **10 fixtures** in Matchday 2 (`PL:2026-27:2`).

- `all_covered`: **true**
- Missing rows: **none**
- Fallback rows: **none**
- Every listed prediction has status: **`ok`**

## Forecast comparison

### Broad areas of agreement

Excluding the intentionally neutral uniform baseline, the models generally favor the home side in:

| Fixture | Consensus direction | Notes |
|---|---|---|
| Liverpool vs Nottingham Forest | Liverpool win | All non-uniform models favor Liverpool; LLM home-win estimates range from **50.0% to 58.7%**. |
| Bournemouth vs Everton | Bournemouth win | All non-uniform models favor Bournemouth, though Grok is comparatively cautious at **38.7%** home-win probability. |
| Leeds United vs Brentford | Leeds win | All non-uniform models narrowly favor Leeds. |
| Sunderland vs Fulham | Sunderland win | All non-uniform models favor Sunderland. |
| Manchester United vs Ipswich Town | Manchester United win | All non-uniform models favor Manchester United; LLM estimates range from **55.0% to 61.5%**. |

There is also strong agreement among the LLM forecasts on the two clearest away-favorite fixtures:

- **Crystal Palace vs Manchester City:** LLM away-win probabilities range from **60.7% to 66.0%** for Manchester City.
- **Aston Villa vs Arsenal:** LLM away-win probabilities range from **50.9% to 56.0%** for Arsenal.

### Main divergences

| Fixture | Key disagreement |
|---|---|
| **Coventry City vs Hull City** | The largest divergence of the matchday. `baseline/b4-dixonceoles` assigns Hull City a **91.4%** away-win probability and Coventry only **0.4%**, while the LLM forecasts are much closer and mostly favor Coventry. Kimi gives Coventry **45.6%**, while Grok is the only LLM to favor Hull (**39.3%** away). |
| **Tottenham Hotspur vs Newcastle United** | `baseline/b4-dixonceoles` favors Newcastle (**41.6%** away), whereas every LLM forecast favors Tottenham, with home-win probabilities from **37.8% to 43.3%**. |
| **Chelsea vs Brighton & Hove Albion** | Most models favor Chelsea, but GLM narrowly favors Brighton (**38.0% away** vs **37.3% home**). DeepSeek is also notably cautious on Chelsea, assigning only **39.7%** to a home win. |
| **Crystal Palace vs Manchester City** | The LLMs and Dixon–Coles baseline strongly favor Manchester City, but the home and ClubElo baselines favor Crystal Palace. |
| **Aston Villa vs Arsenal** | The LLMs and Dixon–Coles baseline favor Arsenal, while the home and ClubElo baselines favor Aston Villa. |

### Notable probabilities

- The most extreme single forecast is `baseline/b4-dixonceoles` for **Hull City to beat Coventry City: 91.4%**, alongside just **0.4%** for a Coventry win.
- `baseline/b4-dixonceoles` also gives **Manchester United a 74.7%** chance against Ipswich Town, well above the LLM range of **55.0%–61.5%**.
- The LLM forecasts are closely aligned on **Manchester City away at Crystal Palace**, all placing City above **60%**.
- Draw probabilities are generally moderate. The highest non-uniform draw forecast is Dixon–Coles’s **31.0%** for **Sunderland vs Fulham**.

## Forecast production cost

| Model | Spend (USD) | Tokens | Samples |
|---|---:|---:|---:|
| `baseline/b1-uniform` | $0.00 | 0 | 10 |
| `baseline/b2-home` | $0.00 | 0 | 10 |
| `baseline/b3-clubelo` | $0.00 | 0 | 10 |
| `baseline/b4-dixonceoles` | $0.00 | 0 | 10 |
| `openrouter/deepseek/deepseek-v4-flash` | $0.00 | 515,318 | 30 |
| `openrouter/moonshotai/kimi-k3` | $0.00 | 149,499 | 30 |
| `openrouter/openai/gpt-5.6-luna` | $0.00 | 60,541 | 30 |
| `openrouter/openai/gpt-5.6-terra` | $0.00 | 28,321 | 30 |
| `openrouter/x-ai/grok-4.5` | $0.00 | 93,927 | 30 |
| `openrouter/z-ai/glm-5.2` | $0.00 | 186,385 | 30 |
| **Total** | **$0.00** | **1,033,991** | **220** |

**Total matchday forecast-production cost: $0.00.**