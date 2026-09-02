# Pass Index — the State of AI, in one file

A daily snapshot of everything sold in the AI market: models, tools, agents
and subscriptions, the companies that make and sell them, their prices, where
they place on public leaderboards, who funded them, and the vocabulary of the
field. Published from [pass.io/index](https://pass.io/index).

- **data/all.json** — the whole catalogue, pretty-printed with sorted keys so
  each daily commit is a readable diff of what the AI market did overnight.
- **data/all.ndjson** — the same, one record per line, for streaming.

Every figure carries its own source and the date it was read. A snapshot is
published only after the nightly consistency checks pass, so a committed dataset
is never a version the checker called false. The date and the day's counts live
in each commit message.

## License

The data in this repository is licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) —
use it for anything, including commercially, as long as you credit
**Pass Index** ([pass.io/index](https://pass.io/index)). Full text in
[LICENSE](LICENSE).
