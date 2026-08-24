# Matchday 1 Forecast Report — 2026–27

## 1. Coverage verification

**Coverage is complete.** The input reports `all_covered: true`, and all **10 models** returned an `ok` forecast for each of the **19 compiled fixture rows**.

| Check | Result |
|---|---|
| Missing forecast rows | None (`missing_rows: []`) |
| Fallback rows | None — every listed prediction has status `ok` |
| Valid samples | Baselines: 1 per compiled row; OpenRouter models: 3 per compiled row |

**Data note:** the 19 compiled rows correspond to **10 distinct fixture IDs**. Nine fixtures appear twice with different manifest hashes but identical listed forecasts; Fulham vs Chelsea appears once.

## 2. Forecast comparison

### Broad agreement among the non-baseline models

| Fixture | Consensus direction | Non-baseline probability range |
|---|---|---|
| Arsenal vs Coventry City | **Arsenal home win** | Home: **68.6%–80.9%** |
| Hull City vs Manchester United | **Manchester United away win** | Away: **51.7%–72.7%** |
| Everton vs Crystal Palace | **Everton home win** | Home: **44.0%–53.2%** |
| Brentford vs Tottenham Hotspur | **Tottenham away win** | Away: **42.7%–66.8%** |
| Manchester City vs Bournemouth | **Manchester City home win** | Home: **57.2%–80.4%** |
| Newcastle United vs Liverpool | **Liverpool away win** | Away: **42.3%–44.0%** |

- **Newcastle vs Liverpool** is the tightest non-baseline agreement: every non-baseline model makes Liverpool the slight away favourite, with away-win probabilities clustered from **42.3% to 44.0%**.
- The strongest home-win views are **GLM-5.2** on **Arsenal vs Coventry** (**80.9% Arsenal**) and **Manchester City vs Bournemouth** (**80.4% Manchester City**).
- **DeepSeek V4 Flash** is notably more bullish on Tottenham at Brentford (**66.8% away win**) than Kimi K3 (**47.0%**), GPT-5.6 Luna (**43.9%**), or Grok-4.5 (**42.7%**).

### Largest divergences

| Fixture | Divergence |
|---|---|
| Ipswich Town vs Sunderland | Split forecast: DeepSeek, Kimi, Luna and Grok favour Ipswich (**40.3%–44.3% home**), while Terra and GLM favour Sunderland (**42.9% and 45.2% away**). |
| Nottingham Forest vs Leeds United | Highly balanced: DeepSeek is virtually even (**37.0% Leeds, 26.0% draw, 37.0% Forest**); Kimi and Grok prefer Forest at **45.0%**, while GLM gives Leeds the highest probability at **37.7%**. |
| Brighton & Hove Albion vs Aston Villa | The non-baseline models are divided: Kimi and Grok prefer Brighton (**42.7%** and **41.3% home**), while DeepSeek, Luna, Terra and GLM lean Aston Villa, led by Terra at **43.4% away**. |
| Fulham vs Chelsea | Most non-baseline models favour Chelsea, ranging from **45.0% to 50.4% away**; DeepSeek instead makes Fulham the most likely winner at **40.2% home**. |

### Notable baseline contrasts

- `baseline/b1-uniform` assigns **33.3%** to each outcome in every row.
- `baseline/b2-home` and `baseline/b3-clubelo` are identical throughout: **45.0% home, 24.0% draw, 31.0% away**.
- `baseline/b4-dixonceoles` is particularly strong on **Brighton vs Aston Villa** (**74.5% Brighton home win**) and **Manchester City vs Bournemouth** (**74.5% Manchester City home win**). Its Brighton forecast contrasts sharply with several non-baseline models that make Aston Villa the more likely winner.

## 3. Forecast-production cost

| Model | Compiled samples | Tokens | Reported spend (USD) |
|---|---:|---:|---:|
| `baseline/b1-uniform` | 19 | 0 | $0.00 |
| `baseline/b2-home` | 19 | 0 | $0.00 |
| `baseline/b3-clubelo` | 19 | 0 | $0.00 |
| `baseline/b4-dixonceoles` | 19 | 0 | $0.00 |
| `openrouter/deepseek/deepseek-v4-flash` | 57 | 913,624 | $0.00 |
| `openrouter/moonshotai/kimi-k3` | 57 | 320,454 | $0.00 |
| `openrouter/openai/gpt-5.6-luna` | 57 | 69,740 | $0.00 |
| `openrouter/openai/gpt-5.6-terra` | 57 | 44,057 | $0.00 |
| `openrouter/x-ai/grok-4.5` | 57 | 183,584 | $0.00 |
| `openrouter/z-ai/glm-5.2` | 57 | 449,306 | $0.00 |
| **Total** | — | **1,980,765** | **$0.00** |

All provider-reported forecast-production costs are **$0.00**, despite **1,980,765** reported tokens across the OpenRouter models.