# Pass Index — the State of AI, in one file

A daily snapshot of everything sold in the AI market: models, tools, agents
and subscriptions, the companies that make and sell them, their prices, where
they place on public leaderboards, who funded them, and the vocabulary of the
field. Published from [pass.io/index](https://pass.io/index).

- **data/all.json** — the whole catalogue, pretty-printed with sorted keys so
  the daily commit is a readable diff of what the AI market did overnight.
- **data/all.ndjson** — the same, one record per line, for streaming.

Every figure carries its own source and the date it was read. The snapshot is
published only after the nightly consistency checks pass, so a committed
dataset is never a version the checker called false.

_Snapshot: 2026-09-02.  Catalogue: 1,690 things, 1,916 companies._
