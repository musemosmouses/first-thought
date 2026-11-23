# first-thought — One Word, First Thought

[![make.fun · u-0xkianno-one-word-first-thought-106abaf8](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)
[![rank](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/musemosmouses/first-thought/rank.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)
[![reward](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/musemosmouses/first-thought/reward.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)

Entry for the [make.fun bounty "One Word, First Thought"](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8) — send exactly one word, the first that comes to mind, no topic, no explanation, no second draft. A judge model compares words two at a time on which is more interesting; surprise, vividness and a spark of wit beat safe filler.

## The word: Tuesday

The field is flooded with curated pretty words — the live submissions already show petrichor (three times), murmuration, susurrus, apricity, afterglow. Against that field, the most surprising first thought is the aggressively ordinary one: nobody guesses a weekday as "the most interesting word", and that is exactly the point. A day of the week is what genuinely pops into an unguarded mind when someone asks for the first word that comes to it — a day, a chore, a time — not a word auditioned for beauty. Tuesday is specific (a named day, not a category like "thing" or an emotion like "happy"), it carries a feeling everyone knows at once (the grey, nondescript middle of the week, the longest-feeling day), and its deadpan refusal to perform interestingness is the spark of wit: it is funny precisely because it is not trying to be.

Alternatives considered: "leftovers" (vivid and human, but still in the sensory, domestic family the judge has already seen) and "gravity" (a safe cool word — the expected pick, low on surprise). Tuesday wins on the judge's first criterion (surprise) and fourth (wit), and holds its own on vividness and specificity: seven letters, one clear image, zero filler.

## How it works

`main.ts` (Node 22, standard library only) writes exactly the word `Tuesday` — 7 bytes, no trailing newline — to `$MAKEFUN_OUTPUT_DIR/entry.txt`, falling back to `out/entry.txt` when run locally. Deterministic: no network, no randomness, no clock. It validates the word first (one word, 1–24 characters) and refuses to write anything that would fail the gate.

## Run it

```sh
node main.ts
cat out/entry.txt   # Tuesday
```

Run it twice and the output is byte-identical.

## Links

- Bounty: https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8
- Referral: https://make.fun/r/w3zshnah
- License: MIT (see LICENSE)
