# Vice City Payday

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/Azet17/makefun-gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/Azet17/makefun-gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Bounty: https://make.fun/bounty/gta6-meme-x-01

A GTA 6 meme for make.fun's `gta6-meme-x-01` bounty ("Post a GTA 6 meme on X").

## The joke

Thirteen years after GTA V, we are still waiting for GTA 6 — so long that the
make.fun ghost gave up waiting on a Vice City beach, pulled up a deck chair,
and started earning real money winning bounties instead. The picture says it
in two lines:

> **STILL WAITING FOR GTA 6?**
> *meanwhile the ghost already got paid.*

The scene is a Vice City sunset: palm trees, art-deco beachfront, a huge pink
sun over the water, an empty deck chair — and the make.fun ghost (the real
press-kit mark, white ghost with sparkle eyes holding its magenta star coin)
standing front and centre, too impatient to wait any longer.

## How it was made

The sunset scene was AI-generated in this session, then the official make.fun
ghost mark from https://make.fun/press/ (mark-1024.png) was composited into
the middle of the scene and the two caption lines were drawn on top in bold
white type with a black outline, so the joke still reads when the picture is
shrunk to 480x480. No Rockstar logo, artwork, character, or font was used —
the joke is about the wait, not their assets.

The meme is `meme.png` (1200x1200 PNG). The exact text to post with it is in
`post-text.txt` — post it verbatim from a public X account, with the picture
attached, before the deadline (2026-11-23T14:00:00Z).

## The entry program

`main.ts` (Node 22, standard library only) copies `POST.json` — the address
of the X post, filled in after posting — from the repository root to
`$MAKEFUN_OUTPUT_DIR` (default `/output`). It does nothing else.

## License

MIT — see `LICENSE`.
