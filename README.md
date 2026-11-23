[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/dukun22/tiny-chess-dukun22/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/dukun22/tiny-chess-dukun22/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess

A chess engine in under 4 KB of Python, written for the
[make.fun bounty](https://make.fun/bounty/tiny-chess-01) of the same name.

`main.py` is the whole engine: a 0x88 board, alpha-beta search with
iterative deepening under a fixed node budget, a transposition table,
quiescence search and a piece-square evaluation. Standard library only,
deterministic, no model calls — the same position always gets the same
move.

Run it against the trial env with `MAKEFUN_ENV_URL` set:

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

Referral: `0y8y43sq` — https://make.fun/r/0y8y43sq
