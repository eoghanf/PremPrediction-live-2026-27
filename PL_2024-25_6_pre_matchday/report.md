# Matchday 6 Forecast Report — 2026–27

## 1. Coverage verification

**Coverage is not complete.** Although the top-level field reports `"all_covered": true` and `missing_rows` is empty, the fixture-level data contains **one missing forecast**:

| Fixture | Model | Status | Valid samples | Fallback indicated? |
|---|---|---:|---:|---|
| Ipswich Town vs Fulham | `openrouter/deepseek/deepseek-v4-flash` | missing | 0 | No |

- All other listed model–fixture rows have `status: ok`.
- **No fallback rows are identified** in the supplied data.
- Therefore, the fixture-level records amount to **99 completed forecasts from 100 expected model–fixture combinations**.

## 2. Forecast comparison

### Broad agreement

- **Arsenal vs Leeds United:** Every non-uniform model favours **Arsenal**; home-win estimates range from **41.4%** (`baseline/b2-home`) to **71.4%** (`openrouter/z-ai/glm-5.2`).
- **Chelsea vs Bournemouth:** All non-uniform models favour **Chelsea**, with home-win probabilities from **41.4%** to **58.1%**.
- **Manchester United vs Tottenham Hotspur:** All non-uniform models favour **Manchester United**, ranging from **41.4%** to **59.3%** for a home win.
- **Sunderland vs Brighton & Hove Albion:** The Dix-on-Ceoles baseline and every available OpenRouter model favour **Brighton**; away-win probabilities run from **43.9%** to **52.3%**. The `b2-home` and `b3-clubelo` baselines instead retain a home-win edge.
- **Coventry City vs Newcastle United:** The Dix-on-Ceoles baseline and all OpenRouter models favour **Newcastle**, at **51.6%–67.1%** away-win probability. Again, `b2-home` and `b3-clubelo` favour the home side.

### Greatest disagreement

| Fixture | Main split |
|---|---|
| **Aston Villa vs Brentford** | The Dix-on-Ceoles baseline and `gpt-5.6-luna` narrowly favour Villa, while DeepSeek, Kimi, Terra, Grok, and GLM favour Brentford. Brentford’s away-win estimates span **31.0%–43.3%** among non-uniform models. |
| **Ipswich Town vs Fulham** | Dix-on-Ceoles strongly favours Fulham (**52.2%** away), whereas every available OpenRouter model favours Ipswich (**40.3%–44.5%** home). DeepSeek is missing for this fixture. |
| **Crystal Palace vs Nottingham Forest** | A near-even contest. Most models narrowly favour Palace, but Dix-on-Ceoles and Grok favour Forest. The highest draw probability is **30.7%** from Grok. |
| **Hull City vs Everton** | The least settled among the available generative forecasts: DeepSeek gives Hull a **42.7%** home-win chance, while Kimi (**38.0%**) and Grok (**36.7%**) favour Everton. Luna, Terra, and GLM narrowly favour Hull. |
| **Liverpool vs Manchester City** | Dix-on-Ceoles and all OpenRouter models favour City, with City away-win probabilities from **42.8%** to **55.6%**. The `b2-home` and `b3-clubelo` baselines favour Liverpool. |

### Notable probabilities

- **Highest home-win probability:** Arsenal over Leeds, **71.4%** from `openrouter/z-ai/glm-5.2`.
- **Highest away-win probability:** Newcastle over Coventry, **67.1%** from `baseline/b4-dixonceoles`.
- **Lowest home-win probability:** Coventry over Newcastle, **8.3%** from `baseline/b4-dixonceoles`.
- The widest non-uniform spread is on **Coventry vs Newcastle home-win probability**: **8.3%** (`b4-dixonceoles`) to **45.0%** (`b3-clubelo`).

## 3. Forecast-production cost

All provider-reported dollar costs are **$0.00**, despite recorded token usage.

| Model | Spend (USD) | Tokens | Samples |
|---|---:|---:|---:|
| `baseline/b1-uniform` | $0.00 | 0 | 10 |
| `baseline/b2-home` | $0.00 | 0 | 10 |
| `baseline/b3-clubelo` | $0.00 | 0 | 10 |
| `baseline/b4-dixonceoles` | $0.00 | 0 | 10 |
| `openrouter/deepseek/deepseek-v4-flash` | $0.00 | 561,765 | 27 |
| `openrouter/moonshotai/kimi-k3` | $0.00 | 136,088 | 30 |
| `openrouter/openai/gpt-5.6-luna` | $0.00 | 73,592 | 30 |
| `openrouter/openai/gpt-5.6-terra` | $0.00 | 26,193 | 30 |
| `openrouter/x-ai/grok-4.5` | $0.00 | 103,940 | 30 |
| `openrouter/z-ai/glm-5.2` | $0.00 | 253,534 | 30 |
| **Total** | **$0.00** | **1,155,112** | **197** |

DeepSeek is the only model below 30 valid samples, consistent with its missing Ipswich Town vs Fulham forecast.