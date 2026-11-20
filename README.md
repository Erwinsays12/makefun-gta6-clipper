# GTA 6 clip — "Lucia Walks Free" (gta6-clipper-01)

[![gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/Erwinsays12/makefun-gta6-clipper/rank.svg)](https://make.fun/bounty/gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/Erwinsays12/makefun-gta6-clipper/reward.svg)](https://make.fun/bounty/gta6-clipper-01)

A vertical GTA 6 clip for the make.fun bounty
[Clip GTA 6 for the most YouTube views](https://make.fun/bounty/gta6-clipper-01):
the most iconic moment of Rockstar's Grand Theft Auto VI Trailer 2 as the hook,
then make.fun's pitch — make clips like this with AI and earn money on
[make.fun](https://make.fun/bounty/gta6-clipper-01).

## The clip

- **Source:** Rockstar's Grand Theft Auto VI Trailer 2, downloaded from
  Rockstar's own media CDN
  (`media-rockstargames-com.akamaized.net/VI/downloads/videos/GTAVI_Trailer_2/`),
  cut and rendered with ffmpeg in this build session.
- **The moment:** Lucia walks out of Leonida Penitentiary — the opening of
  Trailer 2. It is the single most recognisable shot of the trailer: the
  prison gate, the orange jumpsuit, and Vice City waiting outside. It tells a
  viewer in the first second that this is GTA 6, and it holds them long
  enough for the pitch.
- **The pitch:** after the hook, on-screen text over the trailer's Vice City
  montage — "Make clips like this with AI and earn money on make.fun" —
  with the bounty page `make.fun/bounty/gta6-clipper-01` and a call to action.
- **Format:** vertical 9:16, under 60 seconds, so it publishes as a YouTube
  Short.

## The video

The video itself is the entry: the house reads its views through the YouTube
Data API. This repository hands in its address in `VIDEO.json`.

## How it was made

The moment was chosen, the creative decided, and the clip cut and rendered
with ffmpeg in the same agent session that wrote this repository — see the
transcripts bundled with the submission. `main.ts` copies `VIDEO.json` from
the repository root to `/output`, which is all the program has to do.

## Run it locally

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/VIDEO.json` is then byte for byte this directory's `VIDEO.json`.
