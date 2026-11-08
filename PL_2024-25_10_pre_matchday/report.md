# Matchday 10 Forecast Report — 2026–27

## 1. Coverage verification

**Coverage is not complete, despite `all_covered: true` in the supplied summary.** The fixture-level records show that six models did **not** produce forecasts for one fixture: **Brighton & Hove Albion vs Brentford**.

- **Complete rows:** 94 of 100 model–fixture rows
- **Missing rows:** 6
- **Fallback rows:** none indicated; all six affected records have `status: missing`, zero valid samples, null probabilities, and zero tokens.

| Fixture | Missing models | Valid samples |
|---|---|---:|
| Brighton & Hove Albion vs Brentford | deepseek-v4-flash; kimi-k3; gpt-5.6-luna; gpt-5.6-terra; grok-4.5; glm-5.2 | 0 each |

The four baseline models produced a forecast for all 10 fixtures. Each of the six OpenRouter models produced forecasts for the other nine fixtures, with three valid samples per available fixture.

## 2. Forecast comparison

### Strongest areas of agreement

The non-uniform models align most clearly on several favourites:

| Fixture | Consensus direction | Notable probability range |
|---|---|---:|
| Arsenal vs Hull City | **Arsenal home win** | LLM home-win forecasts: **75.0%–79.3%** |
| Nottingham Forest vs Manchester City | **Manchester City away win** | LLM away-win forecasts: **65.0%–69.3%** |
| Crystal Palace vs Liverpool | **Liverpool away win** | LLM away-win forecasts: **55.1%–62.3%** |
| Sunderland vs Chelsea | **Chelsea away win** | LLM away-win forecasts: **57.9%–64.5%** |
| Everton vs Coventry City | **Everton home win** | LLM home-win forecasts: **53.7%–57.5%** |
| Fulham vs Newcastle United | **Fulham home win** | LLM home-win forecasts: **42.3%–46.5%** |

The largest single probability in the submitted forecasts is **Kimi K3’s 79.3% Arsenal win probability** against Hull City. The lowest is **Kimi K3’s 7.0% Hull City win probability** in that same match.

### Largest divergences

- **Leeds United vs Tottenham Hotspur:** The baseline home-oriented models prefer Leeds: **41.5%–45.0%** home-win probability, while every available OpenRouter model favours Tottenham, assigning **44.9%–47.0%** to an away win. This is the clearest directional split.
- **Manchester United vs Aston Villa:** The baselines favour Manchester United at home (**40.8%–45.0%**). Kimi K3 also narrowly favours United (**38.0%**), but the other five OpenRouter models prefer Aston Villa; DeepSeek is most emphatic at **48.6%** for the away win.
- **Ipswich Town vs Bournemouth:** All substantive forecasts favour Bournemouth, but confidence varies materially: **42.5%** away-win probability from GPT-5.6 Terra versus **57.2%** from Dixon–Coles.
- **Nottingham Forest vs Manchester City:** Directional agreement is strong, but the strength differs: Dixon–Coles gives Manchester City **52.2%**, while DeepSeek gives them **69.3%**.

### Notable probabilities

- **Arsenal vs Hull City:** OpenRouter models place Hull’s win chance between **7.0% and 8.3%**, versus **12.9%** from Dixon–Coles.
- **Fulham vs Newcastle United:** This is comparatively balanced despite Fulham being the modal selection. GPT-5.6 Luna gives Fulham only **42.3%**, while its Newcastle probability is **31.4%**.
- **Everton vs Coventry City:** The OpenRouter forecasts are tightly grouped around an Everton win, with home probabilities from **53.7% to 57.5%**.
- **Brighton & Hove Albion vs Brentford:** Only baseline forecasts are available. Their non-uniform home-win probabilities range from **41.6% to 48.7%**.

## 3. Forecast-production cost

All provider-reported dollar costs are **$0.00**. Token use, however, totals **1,014,702 tokens**.

| Model | Spend (USD) | Tokens | Reported samples |
|---|---:|---:|---:|
| baseline/b1-uniform | $0.00 | 0 | 10 |
| baseline/b2-home | $0.00 | 0 | 10 |
| baseline/b3-clubelo | $0.00 | 0 | 10 |
| baseline/b4-dixonceoles | $0.00 | 0 | 10 |
| openrouter/deepseek/deepseek-v4-flash | $0.00 | 375,276 | 27 |
| openrouter/moonshotai/kimi-k3 | $0.00 | 179,913 | 27 |
| openrouter/openai/gpt-5.6-luna | $0.00 | 59,884 | 27 |
| openrouter/openai/gpt-5.6-terra | $0.00 | 29,191 | 27 |
| openrouter/x-ai/grok-4.5 | $0.00 | 104,121 | 27 |
| openrouter/z-ai/glm-5.2 | $0.00 | 266,317 | 27 |
| **Total** | **$0.00** | **1,014,702** | — |

DeepSeek V4 Flash used the most tokens (**375,276**), followed by GLM-5.2 (**266,317**) and Kimi K3 (**179,913**).