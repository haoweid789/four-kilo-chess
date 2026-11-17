# four-kilo-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/haoweid789/four-kilo-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/haoweid789/four-kilo-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine written in under 4,096 bytes of Python (standard library only). It searches with iterative-deepening alpha-beta (negamax), quiescence search, a transposition table, null-move pruning, capped check extensions, repetition avoidance and a fixed node budget per move, and evaluates positions with material plus piece-square tables. Built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=rbrezrwp&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
