# control-pad — how an agent reads this repository

This is the steering wheel. The architect writes here from the Alienware laptop; the MSI
(24-core, RTX 5070 Ti) reads it and drives the Ventus OS Bench; results come back here.
Claude, Codex and the architect all read the same board.

## Read in this order, every time

1. `STATE.md` — what the bench is doing right now, written by the machine. Never edit it.
2. `inbox/` — the architect's notes, newest stamp last. **These are the instructions.**
3. `outbox/QUEUE-FOR-AGENTS.md` — prose notes not yet acted on by an agent. Take the oldest,
   act, then move it to `outbox/DONE.md` with one line saying what you did.
4. `outbox/<stamp>-*.md` — results of orders the watcher already executed.

## Laws

- The pad steers the **Bench** (`Claude-Sandbox-MSI\bench`, a sandbox). Nothing goes live from
  the pad. `order: promote` is the only exception and it always stops to ask the architect.
- `inbox/` is written by the architect only. Agents write to `outbox/` only.
- Stage by explicit path. Commit and push in the same shell call. Pull before every write.
- A note is a file `inbox/<YYYYMMDDHHMM>-<slug>.md`. Optional YAML front matter makes it an
  order (see `inbox/README.md`); otherwise it is prose for the agents.
- Never delete a note. The inbox is the architect's log.
