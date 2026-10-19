# Outings

Recorded Gran Turismo 7 drives ("outings") that [Those Who Run](https://github.com/those-who-run/those-who-run)'s specs and tests rely on.

Each outing is two assets on the [`outings` release](../../releases/tag/outings):

- `<id>.jsonl.gz`: every telemetry frame the engineer received, one JSON object per line. Frames hold GT7's own physics for the player's car (laps, fuel, speed, tyres, in-game position): no account, network or location data.
- `<id>.json`: a sidecar describing the outing (date, track, car, sessions, laps) and why it was archived (a note and the issue that cites it).

How they are made and used is in the main repo's [ADR 0002](https://github.com/those-who-run/those-who-run/blob/main/docs/adr/0002-outing-archive.md) (`those-who-run recordings archive`, `make archive-push`, `make archive-pull`).

Licence: CC BY 4.0 for the recordings.
