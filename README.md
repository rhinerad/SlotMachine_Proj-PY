# Slot Machine (Python)

A command-line slot machine game written in Python while I was learning the language (April 2023).

## How it plays

- Deposit a starting balance, then choose how many lines to bet on (1 to 3) and how much to bet on each line ($1 to $100).
- Each spin fills a 3 x 3 grid with symbols A to D. A line wins when all three symbols match.
- Rarer symbols pay more: A is worth 5x the bet on a line, B 4x, C 3x and D 2x.
- Press Enter to spin again, or `q` to cash out.

## Run it

```
python main.py
```

Requires Python 3. It uses only the standard library.

## What I practiced

Functions, loops, input validation, dictionaries and the `random` module.
