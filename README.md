# makefun-tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/algifarri/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/algifarri/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in Python (0x88 board representation, alpha-beta search with quiescence, MVV-LVA move ordering and piece-square tables), packed into under 4 KB with the official makefun compress tool. This build searches up to 50,000 nodes per move — a change validated head-to-head against the previous 30,000-node build at production time controls (10/12 points over 12 games) and in the kit's practice gauntlet (trial Elo 1279, above the 1154 prize threshold).

## Run it

```sh
python3 main.py
```

The engine speaks the competition's stdin/stdout protocol: send it a position, it answers with its move.

---

<sub>Entered on [make.fun](https://make.fun/?ref=ajkq5baq&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
