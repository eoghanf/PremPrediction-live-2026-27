# Matchday 3 Forecast Report — 2026–27

## Coverage verification

**Complete coverage confirmed.** All 10 models produced an `ok` forecast for each of the 10 fixtures (100 forecast rows total).

- `all_covered`: **true**
- Missing rows: **none**
- Fallback rows: **none recorded**; every submitted prediction has status `ok`.
- Valid-sample counts were consistent by model: baseline models supplied **1** valid sample per fixture, while each OpenRouter model supplied **3**.

## Forecast comparison

The six OpenRouter models agree on the most likely outcome in **all 10 fixtures**. The strongest shared positions are **Manchester City to beat Coventry City** and, with less confidence, several home wins.

| Fixture | OpenRouter consensus outcome | Range of consensus-outcome probability |
|---|---:|---:|
| Ipswich Town vs Liverpool | Liverpool win | 47.0%–59.7% |
| Newcastle United vs Bournemouth | Newcastle win | 49.0%–54.7% |
| Brentford vs Sunderland | Brentford win | 52.0%–61.8% |
| Brighton & Hove Albion vs Leeds United | Brighton win | 46.7%–60.0% |
| Fulham vs Crystal Palace | Fulham win | 39.7%–47.8% |
| Manchester City vs Coventry City | Manchester City win | 79.7%–87.4% |
| Nottingham Forest vs Tottenham Hotspur | Nottingham Forest win | 39.7%–54.4% |
| Hull City vs Aston Villa | Hull City win | 36.3%–57.0% |
| Everton vs Manchester United | Manchester United win | 40.2%–46.0% |
| Arsenal vs Chelsea | Arsenal win | 48.0%–58.3% |

### Agreement and notable differences

- **Strongest agreement:** Manchester City are overwhelming favourites at home to Coventry City. The OpenRouter estimates place a City win between **79.7% and 87.4%**; `baseline/b4-dixonceoles` is similarly emphatic at **86.7%**.
- **Clear home-win agreement:** Newcastle, Brentford, Brighton, Fulham, Nottingham Forest, Hull City, and Arsenal are each favoured by every non-uniform model, although the strength of support varies substantially in some fixtures.
- **Ipswich Town vs Liverpool is the clearest directional split.** All OpenRouter models favour Liverpool (**47.0%–59.7% away-win probability**) and `baseline/b4-dixonceoles` is even stronger on Liverpool (**72.1%**). In contrast, `baseline/b2-home` and `baseline/b3-clubelo` favour Ipswich (**41.9%** and **45.0%**, respectively).
- **Everton vs Manchester United also splits the baseline and modelled forecasts.** The OpenRouter models and `baseline/b4-dixonceoles` favour Manchester United, while `baseline/b2-home` and `baseline/b3-clubelo` retain a home-win preference.
- **Hull City vs Aston Villa has the widest difference in confidence.** Every OpenRouter model still makes Hull the nominal favourite, but their home-win probabilities range from **36.3% to 57.0%**. `baseline/b4-dixonceoles` is much more bullish on Hull at **69.6%**, assigning Aston Villa only **3.9%**.
- **Most balanced forecasts:** Fulham vs Crystal Palace, Nottingham Forest vs Tottenham Hotspur, Hull City vs Aston Villa, and Everton vs Manchester United have the lowest leading probabilities among the OpenRouter forecasts, indicating comparatively open fixtures.
- `baseline/b1-uniform` assigns **33.3%** to each outcome in every fixture and therefore expresses no match-specific preference.

## Forecast-production cost

All provider-reported dollar costs are **$0.00**. Total reported token use was **1,079,601 tokens**.

| Model | Samples | Tokens | Spend (USD) |
|---|---:|---:|---:|
| `baseline/b1-uniform` | 10 | 0 | $0.00 |
| `baseline/b2-home` | 10 | 0 | $0.00 |
| `baseline/b3-clubelo` | 10 | 0 | $0.00 |
| `baseline/b4-dixonceoles` | 10 | 0 | $0.00 |
| `openrouter/deepseek/deepseek-v4-flash` | 30 | 502,023 | $0.00 |
| `openrouter/moonshotai/kimi-k3` | 30 | 138,763 | $0.00 |
| `openrouter/openai/gpt-5.6-luna` | 30 | 59,909 | $0.00 |
| `openrouter/openai/gpt-5.6-terra` | 30 | 30,508 | $0.00 |
| `openrouter/x-ai/grok-4.5` | 30 | 98,713 | $0.00 |
| `openrouter/z-ai/glm-5.2` | 30 | 249,685 | $0.00 |
| **Total** | **220** | **1,079,601** | **$0.00** |