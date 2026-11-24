[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/competitions/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/akbarzn1311/tiny-chess-01/rank.svg)](https://make.fun/competitions/tiny-chess-01/leaderboard)
[![reward](https://make.fun/badge/tiny-chess-01/akbarzn1311/tiny-chess-01/reward.svg)](https://make.fun/competitions/tiny-chess-01)

# tiny-chess-01

A chess engine in Python, packed to 2,666 bytes with `makefun compress`
(readable source: engine.py). 0x88 board, alpha-beta with iterative
deepening on a fixed 300,000-node budget, transposition table, null-move
pruning, killer moves, castling, repetition scoring, quiescence with
futility pruning, incremental material + piece-square eval.

Run: `python3 -P -s main.py` (plays the make.fun env at MAKEFUN_ENV_URL).
