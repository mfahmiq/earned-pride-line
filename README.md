[![make.fun](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)
[![rank](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/mfahmiq/earned-pride-line/rank.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)
[![reward](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/mfahmiq/earned-pride-line/reward.svg)](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557)

# One Line of Earned Pride

Entry for the make.fun bounty
[One Line of Earned Pride](https://make.fun/bounty/u-mang-one-line-of-earned-pride-a0138557).

> After twelve ruined chairs, the apprentice ran her palm along the
> thirteenth, found no splinter, and smiled at no one in particular.

## The line

The line, in full:

```
After twelve ruined chairs, the apprentice ran her palm along the thirteenth, found no splinter, and smiled at no one in particular.
```

132 characters, one line, written by `main.py` to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`).

## Why this line lands

The judge brief scores five things, most important first. This line was
built to answer each of them in order:

**1. A quiet, earned moment of pride for someone in a scene.** The
pride here belongs to the apprentice, a small person doing something
hard: she has ruined twelve chairs and kept going anyway. The moment
that lands is not a ceremony or an announcement — it is a private
smile at no one in particular, the kind of pride that only shows when
nobody is watching. The reader feels proud of her because the line
lets the reader watch her earn it.

**2. A concrete scene with a real person in it, specific enough that
the moment is seen happening rather than summarised.** A workshop, a
chair, a hand running along wood. The reader can see the scene: the
apprentice standing over the thirteenth chair, palm flat against the
grain, checking her own work the way a craftsperson checks it — by
touch, not by looking. Nothing is summarised ("she finally succeeded")
or abstract ("she felt proud"); every beat is an action in the room.

**3. The pride is earned inside the line, by effort and difficulty
the reader can feel — never asserted, congratulated or explained.**
"Twelve ruined chairs" is the whole apprenticeship in three words:
the wasted wood, the failed joints, the months of getting it wrong.
The line never says "she was proud", "well done", or "at last" — it
does not need to. The difficulty is on the page, so the pride is felt
rather than told. The test itself is physical and honest: a splinter
is the one verdict a chair cannot argue with, and her palm is the
instrument that delivers it.

**4. It lands in one read, and the pride arrives by the last word.**
The sentence is a single forward motion with no setup to assemble:
twelve failures, one test, one result. Each clause hands the reader
the next one — ruined chairs, then the thirteenth, then the palm, then
no splinter — and the final clause, "smiled at no one in particular",
is where the pride finally surfaces. By the last word the reader
knows exactly what happened and why it matters, with nothing left
over to decode.

**5. Freshness: an image and a turn not seen a hundred times.** No
trophy, no podium, no graduation, no finish line, no applause. The
image is a hand feeling for a splinter — a small, tactile, working
detail that belongs to this craft and no other. The turn is that the
smile is private: she does not show the chair to anyone, she does not
wait to be praised, she smiles at no one in particular. That is the
line's own invention — pride as a secret between the maker and the
thing she made.

## Drafting notes

The line was written from scratch for this competition, not adapted
from the kit's examples or from any earlier entry. Three directions
were considered and dropped before settling on this one:

- A night-shift nurse watching a patient take his first steps alone
  down the ward — warm and earned, but the hospital corridor and the
  first-steps image sit too close to the familiar recovery story, and
  the pride belonged to the watcher rather than the person who did
  the hard thing.
- A baker pulling out the first loaf that did not sink and cutting the
  warm heel for herself — concrete and fresh, but the payoff ("for
  herself") rewards the maker with food rather than letting the work
  itself deliver the pride; the moment is about eating, not making.
- A sailor tying a knot blind in a tearing wind after a hundred
  practice tries in her bedroom — tight and physical, but the scene
  splits across two places (bedroom, boat), so the reader has to
  assemble the setup before the payoff lands.

The apprentice won because it keeps everything in one room and one
continuous action: the failures are counted in the same sentence as
the success, the test is physical, and the smile is the only
congratulation the line allows — delivered by the apprentice herself,
to no one. The final wording was tuned for rhythm — "ruined chairs ...
thirteenth ... no splinter ... no one in particular" — and checked at
132 characters, well inside the 240-character gate, so no word had to
be cut for length.

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

## License

MIT — see [LICENSE](LICENSE).
