# Matchday 5 Forecast Report — 2026–27

## Coverage verification

**Complete coverage confirmed.** `all_covered` is `true`, and **every one of the 10 models produced a forecast for each of the 10 fixtures**.

- **Missing rows:** none
- **Fallback rows:** none
- **Forecast status:** every listed prediction has status `ok`

Valid-sample totals were 10 for each baseline, 28 for DeepSeek V4 Flash, and 30 for each other LLM model.

## Forecast comparison

### Clear agreement

Excluding the deliberately neutral uniform baseline, the strongest agreement is on several home wins:

| Fixture | Consensus direction | Notable probability range |
|---|---:|---:|
| Everton vs Ipswich Town | Everton home win | 49.7%–63.6% |
| Nottingham Forest vs Coventry City | Nottingham Forest home win | 65.3%–79.4% |
| Leeds United vs Crystal Palace | Leeds home win | 49.1%–62.5% |
| Manchester City vs Sunderland | Manchester City home win | 63.5%–78.1% |

- **Nottingham Forest vs Coventry City** is the most emphatic home-win forecast: DixOnCéoles assigns Forest **79.4%**, while all LLM forecasts place Forest between **65.3% and 72.7%**.
- **Manchester City vs Sunderland** is similarly one-sided among the non-generic forecasts: the LLM home-win range is **72.7%–78.1%**, and DixOnCéoles gives City **63.5%**.
- For **Brighton & Hove Albion vs Arsenal**, the fixture-specific DixOnCéoles model and every LLM favour **Arsenal away** (47.2%–55.5%). The home-favouring baseline outputs are the generic baseline priors rather than fixture-specific agreement.

### Largest divergences

| Fixture | Main disagreement |
|---|---|
| Newcastle United vs Hull City | DixOnCéoles favours **Hull** (43.6%) and gives Newcastle only 21.4%; every LLM instead favours **Newcastle** (39.0%–54.0%). |
| Brentford vs Chelsea | DixOnCéoles and DeepSeek narrowly favour **Brentford**, while Kimi, Luna, Terra, Grok, and GLM favour **Chelsea**. |
| Tottenham Hotspur vs Aston Villa | DixOnCéoles favours **Aston Villa** (40.4%); DeepSeek and Grok make the **draw** their top outcome; Kimi, Luna, Terra, and GLM favour **Tottenham**. |
| Bournemouth vs Liverpool | DixOnCéoles narrowly favours **Bournemouth** (35.2%), but every LLM favours **Liverpool** (39.9%–44.0%). |

### Other notable calls

- **Fulham vs Manchester United:** all LLM models favour **Manchester United away** (46.7%–52.7%), as does DixOnCéoles (39.6%). The generic home-oriented baselines instead lean Fulham.
- **Brentford vs Chelsea** is particularly balanced among the LLMs: Chelsea ranges from **35.0% to 41.3%**, Brentford from **31.7% to 40.2%**, and draws from **23.5% to 28.3%**.
- The highest draw probability in the fixture-specific/LLM set is DeepSeek’s **37.0%** for **Tottenham vs Aston Villa**, where it marginally ranks the draw ahead of a Tottenham win (36.2%).

## Forecast-production cost

All provider-reported dollar costs are **$0.00**. Total reported token usage was **1,215,515 tokens**.

| Model | Valid samples | Tokens | Spend (USD) |
|---|---:|---:|---:|
| `baseline/b1-uniform` | 10 | 0 | $0.00 |
| `baseline/b2-home` | 10 | 0 | $0.00 |
| `baseline/b3-clubelo` | 10 | 0 | $0.00 |
| `baseline/b4-dixonceoles` | 10 | 0 | $0.00 |
| `openrouter/deepseek/deepseek-v4-flash` | 28 | 530,772 | $0.00 |
| `openrouter/moonshotai/kimi-k3` | 30 | 173,899 | $0.00 |
| `openrouter/openai/gpt-5.6-luna` | 30 | 77,571 | $0.00 |
| `openrouter/openai/gpt-5.6-terra` | 30 | 27,555 | $0.00 |
| `openrouter/x-ai/grok-4.5` | 30 | 107,281 | $0.00 |
| `openrouter/z-ai/glm-5.2` | 30 | 298,437 | $0.00 |
| **Total** | **218** | **1,215,515** | **$0.00** |