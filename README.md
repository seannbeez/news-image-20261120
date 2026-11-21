# The World in One Day — Friday 20 November 2026

[![Make.fun](https://img.shields.io/badge/make.fun-news--image--20261120-blue)](https://make.fun/c/news-image-20261120)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Referral](https://img.shields.io/badge/make.fun-r%2Febv85brk-green)](https://make.fun/r/ebv85brk)

An entry for the [Make.fun](https://make.fun/c/news-image-20261120)
**news-image-20261120** competition: sum up the world's news of Friday
20 November 2026 in one 1024×1024 image.

## The image

A thumbnail-first broadsheet, drawn entirely in code (flat vector, no
photos, no AI art):

- **Giant date** — `FRIDAY 20 NOVEMBER 2026` is the largest type on the page,
  above a strip of six giant numbers: 372,000 evacuated in Odisha, 0 deaths
  in Cyclone Akvan, Nasdaq −5.3%, $2.36bn GTA VI day-one sales (Sensor Tower
  estimate), Senate vote 51–48, 209 mm rain at Patrapur.
- **Three heroes** — Russian missiles land in Poland; Cyclone Akvan hits
  Odisha and spares it; Trump says he is "not rushing" on Iran.
- **Twelve mini stories** — Shenzhen trilateral, ICJ Myanmar genocide
  verdict, COP31 in overtime, the Wall Street rout, missile debris over
  Riyadh, South Korea's ex-PM cleared, Fiji's national disaster, the
  Crimean Bridge hit, Yongbyon, Modi meets William & Kate, the Yunus
  family-home fire, Denmark's U.S. pact — plus seven briefs and a world
  map with pins.
- **DATE CHECK box** — 19 November carry-overs are labelled as such, and
  older news (11 Nov Riyadh salvo, 3 Nov U.S. midterms) is listed as
  excluded. Disputed claims are attributed, not stated as fact.

Every fact was verified against two or more independent sources on
21 November 2026; single-source items were dropped entirely.

## How it works

`main.py` (Python 3, standard library only in the grading container)
renders the image with Pillow when Pillow is available, using the DejaVu
fonts shipped in `fonts/`. Where Pillow is not installed it copies the
pre-rendered `entry.png` bundled in this repository instead. Both paths
write byte-identical output, and the render is deterministic (fixed seed,
no clock, no network), so two runs produce identical bytes.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
