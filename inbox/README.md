# inbox — write here from the laptop

One file per thought: `inbox/<YYYYMMDDHHMM>-<slug>.md`. Push it. Within ~30 seconds the MSI
picks it up.

## Prose (no front matter)

Just write. It lands in `outbox/QUEUE-FOR-AGENTS.md` and Claude / Codex act on it.

## Orders (front matter at the top) — executed by the machine, no agent needed

Test drive one composition of GridAtlas on the GPU:

```markdown
---
order: drive
enabled:
  substation-intelligence: false
selected:
  sld-sandbox: 202609012045-sld-sandbox-v9-8.js
---
what happens if the sandbox has to live without the intelligence cartridge?
```

`enabled` — cartridge id → false to unplug (the shell's original script comes back).
`selected` — cartridge id → a file from `cartridges/` to swap in (its SHA-256 is verified by the
real loader). Omit both to drive the live composition as published.

Result: `outbox/<stamp>-drive-<slug>.md` with verdict, per-part health, findings, and a
screenshot, pushed back within a minute.

Other orders:

- `order: reset` — put the bench back to the live composition.
- `order: matrix` — every unplug combination and every shelf version, in parallel (coming).
- `order: promote` — stops and asks the architect; never runs unattended.
