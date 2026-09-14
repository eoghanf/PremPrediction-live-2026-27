# Matchday 4 Forecast Report — 2026–27 Season

**Matchday key:** `PL:2026-27:4`  
**Fixtures:** 10  
**Run:** `live-2026-27`

## 1. Coverage verification

**Coverage is complete.** `all_covered` is `true`: every one of the 10 models produced a forecast for each of the 10 fixtures.

- **Missing rows:** None.
- **Fallback rows:** None reported.
- **Statuses:** All forecast rows are `ok`.
- **Valid samples:** Each baseline supplied **1** valid sample per fixture; each OpenRouter model supplied **3** valid samples per fixture.

## 2. Forecast comparison

### Broad agreement

- **Clear home-win consensus:**  
  - **Chelsea vs Hull City:** all OpenRouter models assign Chelsea **57.0%–69.0%**; the strongest is GLM-5.2 at **69.0%**.  
  - **Crystal Palace vs Ipswich Town:** OpenRouter home probabilities range from **49.7% to 56.6%**.  
  - **Liverpool vs Fulham:** OpenRouter home probabilities range from **60.0% to 65.4%**.
- **Clear away-win consensus:**  
  - **Sunderland vs Arsenal:** OpenRouter models give Arsenal **55.6%–60.3%**.  
  - **Coventry City vs Brighton & Hove Albion:** OpenRouter models give Brighton **55.7%–65.6%**.
- **Moderate home lean:** Aston Villa are favored over Nottingham Forest by every non-uniform model, with home probabilities from **40.3% to 46.3%**.

### Closest and most contested fixtures

| Fixture | Main point of disagreement |
|---|---|
| **Bournemouth vs Brentford** | Most models give Bournemouth a narrow edge, but Grok-4.5 instead makes Brentford the most likely winner (**36.0% away** vs **35.3% home**). |
| **Tottenham Hotspur vs Everton** | Models split directionally: DeepSeek strongly favors Everton (**44.8% away**), while Kimi-K3 favors Tottenham (**40.7% home**). Several others are near-even. |
| **Manchester United vs Manchester City** | Most OpenRouter models favor Manchester City, led by GLM-5.2 at **46.3% away**; DeepSeek is the exception, narrowly favoring Manchester United (**39.7% home** vs **37.5% away**). |
| **Leeds United vs Newcastle United** | A highly balanced fixture. DeepSeek and Kimi-K3 favor Leeds at about **41.4%**, while GPT-5.6-Terra favors Newcastle at **40.2%**. Dixonceoles is virtually level (**35.8% home**, **35.6% away**). |

### Largest divergence and notable probabilities

- **Chelsea vs Hull City is the largest outlier case.** Dixonceoles forecasts only **8.7%** for a Chelsea home win, instead assigning Hull City **50.4%** and the draw **40.9%**. Every OpenRouter model, by contrast, makes Chelsea the clear favorite, at **57.0%–69.0%**.
- **Brighton’s away-win probability is notably strong.** DeepSeek assigns Brighton **65.6%** at Coventry, the highest away-win probability among the OpenRouter forecasts shown.
- **Liverpool’s home-win case is consistently strong.** The OpenRouter forecasts cluster tightly around Liverpool, with Kimi-K3 highest at **65.4%** and Grok-4.5 lowest at **60.0%**.
- The uniform baseline assigns **33.3%** to each result in every fixture, while the home and ClubElo baselines retain their standard home-lean probabilities across most fixtures. This contrasts with the fixture-specific Dixonceoles and OpenRouter forecasts.

## 3. Forecast-production cost

All provider-reported dollar costs are **$0.00**, including the matchday total. Token usage totaled **1,145,500 tokens**.

| Model | Samples | Tokens | Spend (USD) |
|---|---:|---:|---:|
| `baseline/b1-uniform` | 10 | 0 | $0.00 |
| `baseline/b2-home` | 10 | 0 | $0.00 |
| `baseline/b3-clubelo` | 10 | 0 | $0.00 |
| `baseline/b4-dixonceoles` | 10 | 0 | $0.00 |
| `openrouter/deepseek/deepseek-v4-flash` | 30 | 505,789 | $0.00 |
| `openrouter/moonshotai/kimi-k3` | 30 | 160,161 | $0.00 |
| `openrouter/openai/gpt-5.6-luna` | 30 | 54,511 | $0.00 |
| `openrouter/openai/gpt-5.6-terra` | 30 | 27,848 | $0.00 |
| `openrouter/x-ai/grok-4.5` | 30 | 102,018 | $0.00 |
| `openrouter/z-ai/glm-5.2` | 30 | 295,173 | $0.00 |
| **Total** | **220** | **1,145,500** | **$0.00** |