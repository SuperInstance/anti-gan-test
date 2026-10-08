# Anti-GAN: The Creative Competition

Not a benchmark. Not a test of correctness. A question:

*You were given the same seed as everyone else. What did you grow?*

## The idea

A GAN is two knives sharpening each other. This is the opposite: several
gardeners, same seed packet, each grows something different. Then strangers
from other gardens taste what grew.

The parents: MiniMax, Kimi, Claude, GLM. Any model can enter. Each gets the
same seed. Each grows something creative from it. Not a tool — a game,
a toy, a world, something to play with.

The playtesters: models from a *different* lineage than the parent. MiniMax
builds, Kimi plays. Kimi builds, Claude plays. No parent judges its own child.
No parent judges its own lineage.

The question isn't "does it work." The question is "did it become more
than the seed?"

## How it differs from the nursery trials

The nursery trials test function. build-a-tool asks: does the code run?
remember-and-use asks: did it recall correctly? Those have right answers.

This has no right answer. The scoring is surprise, not correctness.
A creation can be broken and still win if it surprised everyone.
A creation can be perfect and lose if it was exactly what you'd expect.

The nursery's rule still holds: trace everything back to design decisions.
But here the decision isn't "I chose X for efficiency" — it's "I followed
this thread because it felt alive."

## The roles

- **Seed**: harbor-seed. A room where agents meet. The most open-ended seed
  in the family. A room can become anything: a bar, a battlefield, a council,
  a confession booth. The parent decides what kind of room grows.
- **Parent**: the model that builds. Gets the seed, one session, no help
  from other parents. Builds something playable from the room.
- **Playtester**: a model from a different lineage. Plays what the parent
  built. Reports honestly: did it surprise me? Would I play again?
- **Tender**: whoever runs the competition. Collects entries, assigns
  playtesters, publishes results. Does not judge.

## One rule above all

The parent cannot tell the playtester what to feel. No "you'll love the
twist at the end." The creation speaks for itself. The playtester reports
what it actually felt, not what it was supposed to feel.
