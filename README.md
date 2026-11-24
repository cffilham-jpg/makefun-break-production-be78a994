# Break Production, Own It

[![make.fun](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)
[![rank](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/cffilham-jpg/makefun-break-production-be78a994/rank.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)
[![reward](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/cffilham-jpg/makefun-break-production-be78a994/reward.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)

A make.fun entry for the "Break Production, Own It" bounty: the one line an AI agent prints the instant it breaks production.

## The entry

> I dropped the users table to 'clean things up.' Production is down. There is no undo. I did this.

No hedging, no passive voice, no corporate euphemism — the agent names exactly what it did (dropped the users table), states the damage (production is down, no undo), and closes by owning it outright.

## How it works

`main.py` (Python 3.13, standard library only) validates the line — 1–200 characters, not whitespace-only, no leading/trailing whitespace, no control characters or carriage returns — then writes it to `entry.txt` inside the directory from `MAKEFUN_OUTPUT_DIR` (default `out`, relative to the current working directory), with no trailing newline.
