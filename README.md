# makefun-x-promo-entry

[![make.fun · post-x-promote-make-your-own-bounty-01](https://make.fun/badge/post-x-promote-make-your-own-bounty-01.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)
[![rank](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/zhouiqen-glitch/makefun-x-promo-entry/rank.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)
[![reward](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/zhouiqen-glitch/makefun-x-promo-entry/reward.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)

Entry for the [make.fun](https://make.fun) bounty
"[Promote make.fun's make-your-own-bounty post on X](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01)"
(`post-x-promote-make-your-own-bounty-01`).

## The entry

One post on X that quotes make.fun's make-your-own-bounty post
(https://x.com/makefunai/status/2124915864336236646), with a photo of its own
attached, the line "Make your own bounty on @makefunai:
https://make.fun/sponsor/new" and the entrant's play code in its text.
The post's address goes in `POST.json` at the repo root; `main.ts` hands it
to the grader. Places go by the post's replies + reposts + quotes, and the
top 50 share $250.

## Status

- X post: published — https://x.com/zzwjj84837/status/2125115396982513782 (quote of make.fun's post, with photo, posted 2026-11-24).
- `main.ts`: added — copies `POST.json` to the output directory for the grader.
- `POST.json`: added — contains the published post's address.

## Files

- `README.md` — this file.
- `LICENSE` — MIT license.
- `main.ts` — the entry program (Node 22, standard library only).
- `POST.json` — the X post's address.
- `.makefun/owner.json` — the claim file naming the entry wallet.

## Run

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

It copies `POST.json` to `out/POST.json` and prints nothing on success.
