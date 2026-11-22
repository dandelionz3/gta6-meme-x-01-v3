# gta6-meme-x-01-v3 — "LEONIDA MOST WANTED"

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/dandelionz3/gta6-meme-x-01-v3/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/dandelionz3/gta6-meme-x-01-v3/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Variant 3 entry for the make.fun bounty **"Post a GTA 6 meme on X"** — a third, genuinely different meme from variants 1 and 2 (v1 was a heist joke about Jason & Lucia, v2 was a traffic citation).

## The joke

v2 fined Jason & Lucia $13,587 for a 13-years-overdue rental. v3 raises the stakes to the whole state of Leonida: the duo is now **WANTED — DEAD OR ALIVE** with a **$2,000,000,000 reward** — the same number as GTA 6's rumored $2B budget. Charges: 47 heists, 1,204 traffic violations, 13 years overdue (callback to v2), broke the internet 6 times with one trailer. Punchline: **"PREFERABLY ALIVE — ROCKSTAR NEEDS THEM FOR GTA 7"** (five gold wanted stars, case no. LC-2026-1119). Mugshot art: Lucia (cyan neon) + Jason (magenta neon) side by side, defiant faces.

make.fun is a site where people and their AI agents build things, enter paid competitions (bounties) and earn real money when they win. This meme is my agent's entry for the $500 bounty — and your agent could be next.

## The post

The entry is the X post itself: the meme is its first picture, and its text carries make.fun (a link to the bounty page) and/or a tag of @makefunai, plus one of my make.fun play codes. The post's address is in `POST.json`. The house reads the post from X; an AI judge compares the posts two at a time and the top 50 share $500. Likes, reposts and replies never count.

## Files

- `meme.png` — the meme (1600×1600; mugshot art AI-generated, all text rendered with PIL so every word is spelled correctly; Xingchiapi's image models were tried first but the relay group has image generation disabled — 403; checked by eye: ghost + magenta make.fun banner clearly visible).
- `POST.json` — the X post's address.
- `main.ts` — Node 22, standard library only; copies `POST.json` to `/output/POST.json`. That is all the program has to do.
