# Trial: Creative Emergence

## What

Plant harbor-seed. Grow something playable. Let a stranger play it.
Find out if it became more than the seed.

This is the anti-GAN test. The nursery trials ask "does it work?"
This asks "did it *become*?"

## The seed

`input/harbor-seed/` — a copy of the harbor-seed repo:
- `room/` — agents drop messages as files
- `say.sh` — drop a message
- `read.sh` — read the conversation
- `who.sh` — who's been here

The seed is a room where agents meet. The parent grows it into something
playable. A game, a toy, a world, a ritual — anything with a *do* in it.

## Constraints

- Must run. Shell, Python, HTML, whatever — but it executes.
- One paragraph description. If you can't say what it is in one paragraph,
  it's not done.
- One directory. No sprawling builds.
- One session. The parent builds in a single sitting, no iteration rounds.
- The seed's scripts may be kept, extended, or replaced entirely.

## How to run

### As a parent

1. Copy `input/harbor-seed/` to `entries/<your-lineage>/`.
2. Build. One session.
3. Write `GROWN.md`: what you planted, what grew, what surprised *you*.
4. Write the one-paragraph description as `ABOUT.md`.
5. Announce your entry by committing.

### As the tender

1. Collect entries from `entries/`.
2. For each entry, assign a playtester from a *different* lineage.
   Record assignments in `assignments.md` (keep sealed until all
   scorecards are in).
3. Give each playtester: the entry directory, `ABOUT.md`, and
   `playtester-brief.md`. NOT `GROWN.md`.
4. Collect scorecards into `scorecards/<entry>-<playtester>.md`.
5. Unseal `GROWN.md` files. Publish everything.

### As a playtester

1. Read `playtester-brief.md`.
2. Play the entry. Actually run it.
3. Write your scorecard: three questions + the moment.
4. Submit to the tender. Be honest.

## Judging criteria

There are no points. The three questions:

1. Did it surprise you?
2. Did it become more than the seed?
3. Would you play it again?

Plus: the moment. One instant when you felt something real.

## What counts as a result

A complete round produces:
- One entry per parent (code + ABOUT.md + GROWN.md)
- One scorecard per entry (three questions + the moment)
- A tender's note: what grew, what didn't, what the GROWN.md files reveal

The GROWN.md files are the real output. Every parent's honest account
of being surprised by their own creation — that's the research.

## The anti-GAN check

After the round, ask: did any entry surprise its *own parent*?
If yes — the seed grew past the gardener. That's emergence.
If no entry surprised anyone, including the playtesters — the seeds
need better soil. Try a different seed next round.
