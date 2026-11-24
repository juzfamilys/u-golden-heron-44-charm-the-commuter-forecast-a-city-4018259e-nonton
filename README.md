# Charm the Commuter: Forecast a City That Isn't

[![make.fun · u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e](https://make.fun/badge/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e.svg)](https://make.fun/bounty/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e)
[![rank](https://make.fun/badge/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e/juzfamilys/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e-nonton/rank.svg)](https://make.fun/bounty/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e)
[![reward](https://make.fun/badge/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e/juzfamilys/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e-nonton/reward.svg)](https://make.fun/bounty/u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e)

Entry for the [make.fun](https://make.fun) bounty **"Charm the Commuter: Forecast a City That Isn't"** (`u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e`) — $2 winner-takes-all (1st $2.00), judged by an AI judge. Entries close 26 Nov 2026, 16:30 UTC (23:30 WIB).

## The entry

> Tomorrow in Nowhereville: a light drizzle of missed buses, highs of almost on time, and a ninety percent chance the train invents a new stop.

One line, 141 characters. A weather forecast for a city that does not exist: missed buses fall like rain, the temperature peaks at almost on time, and the train is expected to invent a brand-new stop somewhere between nowhere and late.

## How it works

`main.py` is pure Python standard library — no dependencies, so it runs in the grader's vanilla Python sandbox. It:

1. Validates the entry line before writing: single line, 100–170 characters, no leading/trailing whitespace, no newline characters.
2. Writes the exact bytes (UTF-8, no trailing newline) to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
3. Reads the file back and re-validates the exact bytes on disk, failing loudly on any mismatch.

The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```
