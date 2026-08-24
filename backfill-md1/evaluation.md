# Matchday 1 backfill — retrospective evaluation (9 games)

Each enrolled OpenRouter entrant read only its two team reports plus the fixture card, authored offline (no web search) and frozen at each game's historical T-24h. Predictions are retrospective: they were made after the matches were played and are scored against the real results. They are NOT temporally anchored (commitments post-date kickoff).

## Arsenal vs Coventry City
- **Result:** 3-0 (H)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.422 | 0.246 | 0.332 | 1.55 | 1.35 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.686 | 0.192 | 0.122 | 2.22 | 0.82 |
| openrouter/moonshotai/kimi-k3 | ok | 0.740 | 0.166 | 0.093 | 2.37 | 0.73 |
| openrouter/openai/gpt-5.6-luna | ok | 0.728 | 0.178 | 0.094 | 2.13 | 0.57 |
| openrouter/openai/gpt-5.6-terra | ok | 0.785 | 0.142 | 0.073 | 2.42 | 0.48 |
| openrouter/x-ai/grok-4.5 | ok | 0.720 | 0.180 | 0.100 | 2.35 | 0.68 |
| openrouter/z-ai/glm-5.2 | ok | 0.809 | 0.130 | 0.061 | 2.68 | 0.62 |

## Hull City vs Manchester United
- **Result:** 2-0 (H)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.422 | 0.246 | 0.332 | 1.55 | 1.35 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.204 | 0.237 | 0.559 | 0.83 | 1.69 |
| openrouter/moonshotai/kimi-k3 | ok | 0.237 | 0.247 | 0.517 | 1.02 | 1.78 |
| openrouter/openai/gpt-5.6-luna | ok | 0.181 | 0.238 | 0.581 | 0.82 | 1.68 |
| openrouter/openai/gpt-5.6-terra | ok | 0.095 | 0.178 | 0.727 | 0.62 | 2.15 |
| openrouter/x-ai/grok-4.5 | ok | 0.180 | 0.257 | 0.563 | 0.92 | 1.75 |
| openrouter/z-ai/glm-5.2 | ok | 0.110 | 0.207 | 0.683 | 0.70 | 2.15 |

## Everton vs Crystal Palace
- **Result:** 2-0 (H)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.422 | 0.246 | 0.332 | 1.55 | 1.35 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.532 | 0.246 | 0.222 | 1.64 | 0.97 |
| openrouter/moonshotai/kimi-k3 | ok | 0.500 | 0.250 | 0.250 | 1.55 | 1.02 |
| openrouter/openai/gpt-5.6-luna | ok | 0.448 | 0.270 | 0.281 | 1.40 | 1.05 |
| openrouter/openai/gpt-5.6-terra | ok | 0.484 | 0.267 | 0.249 | 1.45 | 0.96 |
| openrouter/x-ai/grok-4.5 | ok | 0.440 | 0.277 | 0.283 | 1.37 | 1.10 |
| openrouter/z-ai/glm-5.2 | ok | 0.464 | 0.271 | 0.264 | 1.45 | 1.05 |

## Ipswich Town vs Sunderland
- **Result:** 2-1 (H)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.422 | 0.246 | 0.332 | 1.55 | 1.35 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.421 | 0.298 | 0.281 | 1.33 | 1.07 |
| openrouter/moonshotai/kimi-k3 | ok | 0.443 | 0.263 | 0.293 | 1.43 | 1.14 |
| openrouter/openai/gpt-5.6-luna | ok | 0.403 | 0.283 | 0.313 | 1.30 | 1.12 |
| openrouter/openai/gpt-5.6-terra | ok | 0.307 | 0.264 | 0.429 | 1.11 | 1.37 |
| openrouter/x-ai/grok-4.5 | ok | 0.430 | 0.287 | 0.283 | 1.35 | 1.13 |
| openrouter/z-ai/glm-5.2 | ok | 0.285 | 0.263 | 0.452 | 1.10 | 1.45 |

## Nottingham Forest vs Leeds United
- **Result:** 0-1 (A)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.422 | 0.246 | 0.332 | 1.55 | 1.35 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.370 | 0.260 | 0.370 | 1.35 | 1.35 |
| openrouter/moonshotai/kimi-k3 | ok | 0.450 | 0.267 | 0.283 | 1.47 | 1.12 |
| openrouter/openai/gpt-5.6-luna | ok | 0.400 | 0.273 | 0.327 | 1.32 | 1.17 |
| openrouter/openai/gpt-5.6-terra | ok | 0.375 | 0.263 | 0.362 | 1.31 | 1.28 |
| openrouter/x-ai/grok-4.5 | ok | 0.450 | 0.273 | 0.277 | 1.42 | 1.12 |
| openrouter/z-ai/glm-5.2 | ok | 0.353 | 0.270 | 0.377 | 1.27 | 1.30 |

## Brentford vs Tottenham Hotspur
- **Result:** 3-0 (H)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.422 | 0.246 | 0.332 | 1.55 | 1.35 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.140 | 0.193 | 0.668 | 0.79 | 1.95 |
| openrouter/moonshotai/kimi-k3 | ok | 0.287 | 0.243 | 0.470 | 1.15 | 1.70 |
| openrouter/openai/gpt-5.6-luna | ok | 0.303 | 0.258 | 0.439 | 1.18 | 1.48 |
| openrouter/openai/gpt-5.6-terra | ok | 0.225 | 0.239 | 0.536 | 1.02 | 1.70 |
| openrouter/x-ai/grok-4.5 | ok | 0.300 | 0.273 | 0.427 | 1.25 | 1.53 |
| openrouter/z-ai/glm-5.2 | ok | 0.230 | 0.230 | 0.540 | 1.07 | 1.78 |

## Brighton & Hove Albion vs Aston Villa
- **Result:** 4-0 (H)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.745 | 0.144 | 0.111 | 2.86 | 1.05 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.322 | 0.279 | 0.399 | 1.10 | 1.27 |
| openrouter/moonshotai/kimi-k3 | ok | 0.427 | 0.255 | 0.318 | 1.45 | 1.22 |
| openrouter/openai/gpt-5.6-luna | ok | 0.354 | 0.274 | 0.373 | 1.33 | 1.35 |
| openrouter/openai/gpt-5.6-terra | ok | 0.309 | 0.257 | 0.434 | 1.18 | 1.46 |
| openrouter/x-ai/grok-4.5 | ok | 0.413 | 0.280 | 0.307 | 1.40 | 1.18 |
| openrouter/z-ai/glm-5.2 | ok | 0.335 | 0.257 | 0.408 | 1.28 | 1.43 |

## Manchester City vs Bournemouth
- **Result:** 2-1 (H)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.745 | 0.144 | 0.111 | 2.86 | 1.05 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.572 | 0.240 | 0.188 | 1.70 | 0.97 |
| openrouter/moonshotai/kimi-k3 | ok | 0.748 | 0.156 | 0.096 | 2.50 | 0.78 |
| openrouter/openai/gpt-5.6-luna | ok | 0.740 | 0.163 | 0.097 | 2.18 | 0.68 |
| openrouter/openai/gpt-5.6-terra | ok | 0.729 | 0.173 | 0.098 | 2.23 | 0.67 |
| openrouter/x-ai/grok-4.5 | ok | 0.720 | 0.170 | 0.110 | 2.38 | 0.75 |
| openrouter/z-ai/glm-5.2 | ok | 0.804 | 0.127 | 0.069 | 2.73 | 0.67 |

## Newcastle United vs Liverpool
- **Result:** 2-2 (D)

| Model | Status | p(H) | p(D) | p(A) | λ(H) | λ(A) |
|---|---|---|---:|---:|---:|---:|---:|
| baseline/b1-uniform | ok | 0.333 | 0.333 | 0.333 | - | - |
| baseline/b2-home | ok | 0.450 | 0.240 | 0.310 | - | - |
| baseline/b3-clubelo | ok | 0.450 | 0.240 | 0.310 | 0.91 | 0.75 |
| baseline/b4-dixonceoles | ok | 0.709 | 0.161 | 0.129 | 2.62 | 1.05 |
| openrouter/deepseek/deepseek-v4-flash | ok | 0.310 | 0.257 | 0.433 | 1.18 | 1.48 |
| openrouter/moonshotai/kimi-k3 | ok | 0.320 | 0.250 | 0.430 | 1.28 | 1.58 |
| openrouter/openai/gpt-5.6-luna | ok | 0.314 | 0.252 | 0.434 | 1.27 | 1.53 |
| openrouter/openai/gpt-5.6-terra | ok | 0.324 | 0.248 | 0.429 | 1.32 | 1.57 |
| openrouter/x-ai/grok-4.5 | ok | 0.307 | 0.270 | 0.423 | 1.22 | 1.55 |
| openrouter/z-ai/glm-5.2 | ok | 0.310 | 0.250 | 0.440 | 1.25 | 1.53 |

## Leaderboard (mean RPS, lower is better)

| Model | RPS |
|---|---:|
| baseline/b4-dixonceoles | 0.1955 |
| baseline/b2-home | 0.2093 |
| baseline/b3-clubelo | 0.2093 |
| openrouter/moonshotai/kimi-k3 | 0.2150 |
| openrouter/x-ai/grok-4.5 | 0.2265 |
| openrouter/openai/gpt-5.6-luna | 0.2301 |
| openrouter/deepseek/deepseek-v4-flash | 0.2547 |
| baseline/b1-uniform | 0.2593 |
| openrouter/z-ai/glm-5.2 | 0.2617 |
| openrouter/openai/gpt-5.6-terra | 0.2702 |

