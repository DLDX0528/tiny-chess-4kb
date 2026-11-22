# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/dldx0528/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/dldx0528/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4,003-byte chess engine in pure Python 3.13 standard library: alpha-beta search with quiescence, a transposition table, killer moves, history heuristic, null-move pruning and late-move reductions, a check extension, and a single counter array for material tracking, on a deterministic fixed-node budget (250,000 nodes a move). Local practice trials: 5.5/6 (Elo ~1809) and 4.5/6 (Elo ~1545), two-trial mean ~1677. Built for make.fun's tiny-chess-01 bounty.

## Run it

```sh
python3 main.py
```

The engine talks to the trial environment at `MAKEFUN_ENV_URL` and plays its games over UCI.

---

<sub>Entered on [make.fun](https://make.fun/?ref=bn79sqc3&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
