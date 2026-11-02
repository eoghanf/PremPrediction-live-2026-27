# Matchday 9 Forecast Report — 2026–27

## 1. Coverage verification

**Coverage is complete.** All 10 models produced a forecast for each of the 10 fixtures (**100 forecast rows total**).

- `all_covered`: **true**
- Missing rows: **none**
- Fallback rows: **none listed**
- Every submitted row has status: **`ok`**
- Baseline models supplied **1 valid sample per fixture**; OpenRouter models supplied **3 valid samples per fixture**.

## 2. Forecast comparison

### Broad agreement

Excluding the uniform baseline’s equal 33.3% allocation, the models broadly favour the **home side** in eight fixtures:

| Fixture | Broad model view |
|---|---|
| Chelsea vs Manchester United | Chelsea home win |
| Bournemouth vs Leeds United | Bournemouth home win |
| Brentford vs Nottingham Forest | Brentford home win |
| Coventry City vs Sunderland | Coventry home win, but relatively close |
| Hull City vs Ipswich Town | Hull home win |
| Manchester City vs Brighton & Hove Albion | Manchester City home win |
| Tottenham Hotspur vs Crystal Palace | Tottenham home win |
| Aston Villa vs Fulham | Aston Villa home win |

For **Liverpool vs Arsenal**, the fixture-specific and OpenRouter forecasts favour **Arsenal away**, with away-win probabilities from **39.3% to 44.3%** among the OpenRouter models. The generic home and ClubElo baselines instead retain a Liverpool home-win edge.

### Largest divergences

- **Tottenham Hotspur vs Crystal Palace** has the widest home-win spread among non-uniform models: **44.2%** for `baseline/b4-dixonceoles` versus **72.7%** for DeepSeek. DeepSeek also assigns Crystal Palace only **9.5%** to win.
- **Newcastle United vs Everton** shows the clearest disagreement on the most likely outcome:
  - DeepSeek makes **Everton** the favourite at **49.8%**.
  - All other non-uniform models favour **Newcastle**, ranging from **38.7% to 45.0%** home-win probability.
- **Coventry City vs Sunderland** is relatively balanced. `baseline/b4-dixonceoles` favours Sunderland (**42.0% away**) while the OpenRouter models all lean Coventry (**37.7%–41.6% home**).
- **Hull City vs Ipswich Town** features a strong outlying baseline: `baseline/b4-dixonceoles` gives Hull **60.5%**, compared with **41.0%–45.3%** across the OpenRouter models.

### Notable probabilities

- The highest single win probability is DeepSeek’s **72.7% Tottenham home win** over Crystal Palace.
- GLM also strongly supports Tottenham at **66.2%**.
- `baseline/b4-dixonceoles` gives Hull **60.5%** against Ipswich, notably higher than the language-model forecasts.
- GLM gives Manchester City a **59.2%** home-win probability against Brighton, the strongest City projection in the set.
- Arsenal are favoured away at Liverpool by every OpenRouter model, despite the generic home/ClubElo baselines favouring Liverpool.

## 3. Forecast production cost

| Model | Valid samples | Tokens | Spend (USD) |
|---|---:|---:|---:|
| `baseline/b1-uniform` | 10 | 0 | $0.00 |
| `baseline/b2-home` | 10 | 0 | $0.00 |
| `baseline/b3-clubelo` | 10 | 0 | $0.00 |
| `baseline/b4-dixonceoles` | 10 | 0 | $0.00 |
| `openrouter/deepseek/deepseek-v4-flash` | 30 | 325,712 | $0.00 |
| `openrouter/moonshotai/kimi-k3` | 30 | 115,918 | $0.00 |
| `openrouter/openai/gpt-5.6-luna` | 30 | 89,900 | $0.00 |
| `openrouter/openai/gpt-5.6-terra` | 30 | 26,752 | $0.00 |
| `openrouter/x-ai/grok-4.5` | 30 | 101,076 | $0.00 |
| `openrouter/z-ai/glm-5.2` | 30 | 313,551 | $0.00 |
| **Total** | **220** | **972,909** | **$0.00** |

**Total reported matchday forecast cost: $0.00.**