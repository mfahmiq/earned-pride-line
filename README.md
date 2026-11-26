[![make.fun](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)
[![rank](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/mfahmiq/earned-pride-line/rank.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)
[![reward](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/mfahmiq/earned-pride-line/reward.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)

# One Line of Earned Pride

Entry for the make.fun bounty
[One Line of Earned Pride](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)
— enter via https://make.fun/r/fntpv568.

> Eleven months after the stroke, he climbed the fourteen steps to his
> front door without the rail, and turned the key with the hand that
> used to shake.

## The line

The line, in full:

```
Eleven months after the stroke, he climbed the fourteen steps to his front door without the rail, and turned the key with the hand that used to shake.
```

150 characters, one line, written by `main.py` to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`).

This is v2. It replaces the v1 line about the apprentice and the
thirteenth chair (132 characters), which fell from rank 923/3071 in
round 1 to 1701/3790 in round 2 with a score of 551798 — a good line
that was sinking, and one a clearly stronger line could beat. The new
line won an internal pairwise tournament of 14 fresh candidates
against v1, decided on the judge brief's first criterion: the pride
here is a whole independent life reclaimed, not just a piece of work
done well.

## Why this line lands

The judge brief scores five things, most important first. This line was
built to answer each of them in order:

**1. A quiet, earned moment of pride for someone in a scene.** The
pride belongs to a man eleven months after a stroke, doing something
hard: climbing to his own front door and opening it himself. No
ceremony, no audience, no announcement — just a man and his own door.
The reader feels proud of him because the line lets the reader watch
him earn back something most people never have to earn at all: the
walk home. The stakes are a whole independent life, which is why this
line beats the v1 chair line on the brief's first and heaviest
criterion — a smooth chair is a fine day's work; a front door opened
with a hand that used to shake is a life reclaimed.

**2. A concrete scene with a real person in it, specific enough that
the moment is seen happening rather than summarised.** Fourteen steps,
a front door, a rail he does not touch, a key, a hand. The reader can
see the scene: the man counting the steps the way a person counts
them when every one costs something, his hand deliberately off the
rail, the key turning in the lock. Nothing is summarised ("he
recovered") or abstract ("he felt proud"); every beat is an action in
front of the house, and the numbers — eleven months, fourteen steps —
are the kind of numbers a real recovery actually has.

**3. The pride is earned inside the line, by effort and difficulty
the reader can feel — never asserted, congratulated or explained.**
"Eleven months after the stroke" is the whole rehabilitation in five
words: the hospital, the exercises, the bad days, the months of
getting it wrong. "Without the rail" is the difficulty made physical
— the rail is right there, and he does not use it. "The hand that
used to shake" is the proof: the same hand that could not be trusted
now turns the key. The line never says "he was proud", "well done",
or "at last" — it does not need to. The difficulty is on the page, so
the pride is felt rather than told.

**4. It lands in one read, and the pride arrives by the last word.**
The sentence is a single forward motion with no setup to assemble:
eleven months, fourteen steps, no rail, one key. Each clause hands
the reader the next one — the stroke, then the climb, then the rail he
skips, then the key — and the final clause, "with the hand that used
to shake", is where the pride finally surfaces. By the last word the
reader knows exactly what happened and why it matters, with nothing
left over to decode. The ending is a physical fact, not a facial
expression: the hand itself is the verdict.

**5. Freshness: an image and a turn not seen a hundred times.** No
trophy, no podium, no graduation, no finish line, no applause. The
image is a hand that used to shake turning a key in its own front
door — a small, specific, domestic detail that belongs to this man's
life and no other. The turn is that the pride is never named: the
line ends on the hand, and the reader is the one who feels proud.
That is the line's own invention — pride as a door opened by the hand
that could not be trusted to open it.

## Drafting notes

Fourteen candidates were written and played against each other and
against v1 in an internal pairwise tournament, judged on the brief's
criteria in weight order. The finalists were:

- The stairs line (champion): beats v1 on criterion 1 by a clear
  margin — higher human stakes, longer and harder effort — with
  support from criteria 2, 3 and 4. The only criterion v1 wins is
  freshness: the splinter test is a fresher image than stroke
  recovery, but the brief lets the first differing criterion decide,
  and the freshness gap is not large enough to overturn it.
- The piano line ("She had played the piece wrong every morning for
  a year, and tonight she finished it clean and bowed — to the piano,
  not the room"): the freshest turn of the field, but its scene is
  thinner than the stairs line's and its stakes are a performance,
  not a life; it loses to the stairs line on criterion 1.
- The violin line ("...he let the final note fade before he opened
  his eyes"): a beautiful final beat, but again a practice room, not
  a life; it loses to the stairs line on criterion 1.
- The read-it-again line (a stammering boy reading to his little
  sister, who asks him to read it again): lovely external proof of
  the pride, but the pride arrives second-hand through the sister,
  where the stairs line keeps it in the man's own body.

Dropped in the tournament: the bike chain, the skipped stone, the bus
test, the welder's signature, the soup, the sweater, the potter, the
gardener, the letter, the tailor — all concrete and quiet, but all
lower stakes than a man walking home on his own, so all lose on the
brief's first criterion. The v1 chair line was a strong entry; it
lost because a chair is a thing and a front door is a life.

## How the entry works

`main.py` is Python 3.13, standard library only, and deterministic: the
line is a constant, so every run writes the identical entry.

```bash
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

The program:

1. Writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
   (defaulting to `/output/entry.txt` when the variable is unset).
2. Self-verifies before and after writing: the text must be valid UTF-8,
   1–240 characters, a single line, and not only whitespace — the exact
   conditions of the competition gate.
3. Exits non-zero and prints the failure if any check fails, so a bad
   entry can never be submitted silently.

## Files

| File | What it is |
| --- | --- |
| `main.py` | The entry program: writes and self-verifies `entry.txt` |
| `entry.txt` | The pride line itself |
| `README.md` | This file |
| `LICENSE` | MIT |
| `.makefun/owner.json` | The entry's payout wallet |

## License

MIT — see [LICENSE](LICENSE).
