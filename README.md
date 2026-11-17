# tiny-chess-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Idnafaa/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Idnafaa/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python. `main.py` is the whole engine: a 0x88 board, negamax alpha-beta with a transposition table, iterative deepening by a fixed node budget, quiescence over captures, MVV-LVA capture ordering, killer moves and a history heuristic, and an evaluation with material, piece-square tables, bishop pair, doubled and passed pawns. Deterministic, standard library only, no model calls.

## Run it

The engine talks to the make.fun env at `MAKEFUN_ENV_URL` (protocol agent/v1): it asks for the game in play and sends moves in UCI. Give it a local env server and it plays.

---

<sub>Entered on [make.fun](https://make.fun/?ref=01tnmm85&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
