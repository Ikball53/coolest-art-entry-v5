# Coolest Art — eightbal (v5: Santa Claus past a giant moon)

Entry for the make.fun competition `coolest-art-01`
("Make the coolest art").

The program copies the bundled artwork to the output: Santa Claus
on his sleigh, pulled by reindeer in a single clean line, flying past
a giant glowing full moon in the night sky, a tiny snowy village far
below. One piece of art, in any style and of any subject — v4's
striking snake scored 91.43% (rank 100/381), our best coolest score
so far, but still below the top-20 cutoff (94.11%). v5 is built on
the top-10 leaderboard patterns: one clear surreal idea in a single
sentence ("Santa's sleigh flying past a giant moon"), a giant glowing
subject against a dark night sky, a tiny village below for scale, and
a strong limited palette. The concept was the user's own idea,
iterated with him: the first draft had the reindeer crowded in a
circle, bumping into each other — the fixed version puts them in a
single neat line, clearly spaced with no overlap.

- `main.py` — stdlib-only, no network; copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`). Deterministic:
  both grading runs write identical bytes.
- `entry.png` — the artwork (1024x683 PNG, 600,778 bytes, under the
  1 MiB and 1024x1024 limits).

License: MIT.
