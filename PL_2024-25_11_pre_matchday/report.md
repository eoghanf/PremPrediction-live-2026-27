# Matchday 11 Forecast Report — 2026–27

## 1. Coverage verification

**Complete coverage confirmed.** `all_covered` is `true`, and **every one of the 10 models produced a forecast for each of the 10 fixtures** (100 fixture-model forecasts total).

- **Missing rows:** None (`missing_rows` is empty).
- **Fallback rows:** None indicated; every listed prediction has status **`ok`**.
- Valid samples were consistent by model type: baselines returned **1** valid sample per fixture; OpenRouter models returned **3** valid samples per fixture.

## 2. Forecast comparison

### Broad agreement

Most fixtures have a clear consensus on the likely winner:

| Fixture | Consensus direction | Notes |
|---|---|---|
| Manchester City vs Fulham | Manchester City win | All non-uniform models favour City; home-win estimates range from **41.7%** (b2-home) to **64.6%** (GPT-5.6-terra). |
| Aston Villa vs Sunderland | Aston Villa win | All non-uniform models favour Villa; DeepSeek is most bullish at **65.5%**. |
| Bournemouth vs Nottingham Forest | Bournemouth win | All non-uniform models favour Bournemouth; LLM home-win estimates run from **53.7%** (Grok) to **60.9%** (DeepSeek). |
| Chelsea vs Leeds United | Chelsea win | All non-uniform models favour Chelsea; estimates range from **51.3%** (Grok) to **60.6%** (GPT-5.6-terra). |
| Tottenham Hotspur vs Ipswich Town | Tottenham win | All non-uniform models favour Spurs; GLM-5.2 is highest at **64.5%**. |
| Liverpool vs Manchester United | Liverpool win | All non-uniform models favour Liverpool; DeepSeek gives the strongest home-win probability of the matchday, **67.1%**. |

### Greatest divergences

| Fixture | Main disagreement |
|---|---|
| **Hull City vs Brighton & Hove Albion** | The generic home baselines favour Hull (**41.7%–45.0%** home), but b4-dixonceoles and every OpenRouter model favour Brighton. Away-win estimates range from **31.0%** (b3-clubelo) to **60.2%** (DeepSeek). |
| **Newcastle United vs Arsenal** | b2-home and b3-clubelo favour Newcastle, while b4-dixonceoles and all six OpenRouter models favour Arsenal. Arsenal’s away-win probability ranges from **45.5%** (GPT-5.6-luna) to **55.6%** (b4-dixonceoles). |
| **Brentford vs Everton** | The closest and most divided fixture. DeepSeek (**36.7%**) and Grok (**37.7%**) narrowly favour Everton, while b2-home, b3-clubelo, b4-dixonceoles, Kimi, Luna, Terra, and GLM favour Brentford. Kimi is nearly even: **37.8% Brentford, 35.3% Everton, 27.0% draw**. |
| **Coventry City vs Crystal Palace** | Most models favour Coventry, but b4-dixonceoles marginally makes Palace the favourite (**36.7% away vs 36.6% home**). Terra is much more positive on Coventry (**59.3%**) than Kimi, Luna, and Grok (**48.3%–48.7%**). |

### Notable probabilities

- **Liverpool over Manchester United** is the strongest single win call: DeepSeek assigns Liverpool **67.1%**.
- **Brighton away at Hull** is a strong away consensus among the data-sensitive forecasts: DeepSeek gives Brighton **60.2%** and GLM-5.2 **59.3%**.
- **Arsenal away at Newcastle** is also a clear away-favourite call outside the generic home baselines, with five models at or above **50%** for Arsenal.
- The lowest listed non-uniform win probability is GLM-5.2’s **17.4%** for Hull to beat Brighton; DeepSeek gives Manchester United only **12.8%** to win at Liverpool.

## 3. Forecast-production cost

| Model | Samples | Tokens | Spend (USD) |
|---|---:|---:|---:|
| baseline/b1-uniform | 10 | 0 | $0.00 |
| baseline/b2-home | 10 | 0 | $0.00 |
| baseline/b3-clubelo | 10 | 0 | $0.00 |
| baseline/b4-dixonceoles | 10 | 0 | $0.00 |
| openrouter/deepseek/deepseek-v4-flash | 30 | 399,239 | $0.00 |
| openrouter/moonshotai/kimi-k3 | 30 | 175,203 | $0.00 |
| openrouter/openai/gpt-5.6-luna | 30 | 96,690 | $0.00 |
| openrouter/openai/gpt-5.6-terra | 30 | 33,314 | $0.00 |
| openrouter/x-ai/grok-4.5 | 30 | 112,259 | $0.00 |
| openrouter/z-ai/glm-5.2 | 30 | 304,003 | $0.00 |
| **Total** | **220** | **1,120,708** | **$0.00** |

All provider-reported forecast-generation costs were **$0.00**, despite **1,120,708 tokens** recorded across the six OpenRouter models.