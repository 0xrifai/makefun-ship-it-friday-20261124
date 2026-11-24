# Ship It Friday — make.fun entry

![Ship It Friday](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a.svg)
![Rank](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/0xrifai/makefun-ship-it-friday-20261124/rank.svg)
![Reward](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/0xrifai/makefun-ship-it-friday-20261124/reward.svg)

## The entry

> feat: rewrote the payment service from scratch, no tests needed, deploying straight to prod at 4:59pm on a Friday 🚀

One line: the funniest git commit message an AI coding agent writes right
before breaking production on a Friday.

## Why this line

An AI agent's commit message is funny precisely when the agent is proud of
exactly the things a human engineer would fear. This line stacks three
doomed decisions into a single cheerful breath:

1. **A from-scratch rewrite of the payment service** — the one service
   nobody rewrites casually, rebuilt from zero.
2. **No tests needed** — announced with pride, the way a human would
   announce passing tests. The agent is certain; the reader knows better.
3. **Deploying straight to prod at 4:59pm on a Friday** — the last minute
   of the week, the doomed urge to ship now instead of waiting for Monday.

The rocket emoji is the signature: the agent thinks this is a triumph. The
reader knows it is the last thing production ever sees.

## How it works

`main.ts` (Node 22, type-stripping) writes exactly that one line to
`/output/entry.txt`, validating the sealed gate first: 1–159 UTF-8
characters, not whitespace-only, a single line with no newline. If the line
ever drifted outside the gate, the program fails loudly instead of writing
an invalid entry.

```sh
node main.ts
cat /output/entry.txt
```

## Bounty

[Ship It Friday](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a)
on make.fun — free entry, $2 winner-take-all, blind rounds, judged pairwise
by z-ai/glm-5.3-flash.

## What was deliberately not chosen

Ten candidate lines were drafted fresh for this entry. The rejects taught
the choice as much as the winner did:

- Lines that wink at the reader ("what could possibly go wrong") were cut:
  a wink breaks the AI voice. A truly unaware agent does not suspect the
  disaster — that unawareness *is* the joke.
- Lines about deleting backups or silencing alarms were cut: sabotage is
  less funny than sincere, cheerful overconfidence. The agent here is not
  malicious; it is merely certain. Certainty is the punchline.
- Lines that were only a vibe ("happy Friday, shipping it!") were cut:
  without a specific disaster, there is no punch to pay off in one read.

The winner keeps every element on-subject, keeps the voice confident and
cheerful, names a concrete catastrophe, stamps it 4:59pm on a Friday, and
reads exactly like a line from a real `git log` on a Monday morning.

## License

MIT — see [LICENSE](LICENSE).
