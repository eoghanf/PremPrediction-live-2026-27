# Matchday 7 Forecast Report — 2026–27

## Coverage verification

**Complete coverage confirmed.** `all_covered` is `true`, and there are **no missing or fallback rows** (`missing_rows: []`).

- All **10 models** returned a forecast for each of the **10 fixtures**.
- Every listed forecast has status **`ok`**.
- Baseline models supplied **1 valid sample** per fixture; each OpenRouter model supplied **3 valid samples** per fixture.

## Forecast comparison

### Broad agreement

The models were directionally aligned on most fixtures:

| Fixture | Predominant most-likely outcome | Agreement summary |
|---|---:|---|
| Everton vs Chelsea | Everton win | 8 models prefer Everton; Dixonceoles narrowly prefers Chelsea; uniform is tied. |
| Brentford vs Liverpool | Brentford win | All non-uniform models prefer Brentford. |
| Fulham vs Hull City | Split | 6 models prefer Fulham, while Dixonceoles, GPT-5.6 Terra, and Grok prefer Hull; uniform is tied. |
| Manchester City vs Ipswich Town | Manchester City win | All non-uniform models prefer Manchester City. |
| Newcastle United vs Aston Villa | Newcastle win | All non-uniform models prefer Newcastle. |
| Bournemouth vs Sunderland | Bournemouth win | All non-uniform models prefer Bournemouth. |
| Brighton & Hove Albion vs Crystal Palace | Brighton win | All non-uniform models prefer Brighton. |
| Leeds United vs Manchester United | Leeds win | All non-uniform models prefer Leeds. |
| Nottingham Forest vs Arsenal | Arsenal win | Dixonceoles and all six OpenRouter models prefer Arsenal; the two generic home baselines prefer Nottingham Forest; uniform is tied. |
| Tottenham Hotspur vs Coventry City | Tottenham win | All non-uniform models prefer Tottenham. |

The uniform baseline remains exactly **33.33% / 33.33% / 33.33%** throughout. The home baseline and ClubElo baseline select the home side in every fixture, including Nottingham Forest vs Arsenal.

### Largest divergences

- **Fulham vs Hull City** is the clearest directional split.  
  - Fulham-win probabilities range from **28.33%** (Grok) to **44.67%** (Kimi).  
  - Hull-win probabilities range from **29.33%** (Kimi) to **43.67%** (Grok).  
  - Dixonceoles, GPT-5.6 Terra, and Grok make Hull the most likely winner, while the other six non-uniform forecasts favor Fulham.

- **Everton vs Chelsea** also has a notable disagreement.  
  - DeepSeek assigns Everton a **56.10%** win probability, the strongest Everton view.  
  - Dixonceoles instead marginally favors Chelsea, **35.97%** to **35.11%** for Everton.

- **Tottenham vs Coventry City** has the widest spread in Tottenham-win confidence among the OpenRouter models: **37.40%** from DeepSeek versus **54.53%** from GPT-5.6 Luna. All still select Tottenham as most likely.

### Notable probabilities

- **Manchester City vs Ipswich Town** is the strongest home-win consensus: Manchester City are assigned **77.67%–86.35%** home-win probability by the non-generic forecasts. Dixonceoles is highest at **86.35%**; GLM-5.2 gives Ipswich only **4.60%** to win.
- **Brighton vs Crystal Palace** is another strong home call: the OpenRouter forecasts place Brighton’s win probability between **57.27%** and **62.80%**.
- **Nottingham Forest vs Arsenal** is the strongest away-win call: OpenRouter models give Arsenal **55.37%–60.00%**, with GPT-5.6 Terra highest at **60.00%**.

## Forecast-production cost

| Model | Tokens | Reported spend (USD) |
|---|---:|---:|
| baseline/b1-uniform | 0 | $0.00 |
| baseline/b2-home | 0 | $0.00 |
| baseline/b3-clubelo | 0 | $0.00 |
| baseline/b4-dixonceoles | 0 | $0.00 |
| openrouter/deepseek/deepseek-v4-flash | 425,243 | $0.00 |
| openrouter/moonshotai/kimi-k3 | 119,518 | $0.00 |
| openrouter/openai/gpt-5.6-luna | 72,674 | $0.00 |
| openrouter/openai/gpt-5.6-terra | 33,867 | $0.00 |
| openrouter/x-ai/grok-4.5 | 93,593 | $0.00 |
| openrouter/z-ai/glm-5.2 | 258,757 | $0.00 |
| **Total** | **1,003,652** | **$0.00** |

All provider-reported forecast-production costs are **$0.00**, despite **1,003,652 total tokens** recorded across the six OpenRouter models.