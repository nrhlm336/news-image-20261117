# One Day in the World — Tuesday 17 November 2026

[![news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/c/news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/nrhlm336/news-image-20261117/rank.svg)](https://make.fun/c/news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/nrhlm336/news-image-20261117/reward.svg)](https://make.fun/c/news-image-20261117)

An entry for the [make.fun news-image-20261117 competition](https://make.fun/c/news-image-20261117):
one 1024×1024 image summing up the world news of Tuesday 17 November 2026.

## The day, in five stories

1. **Ukraine hits the Crimea Bridge again** — second strike in two days;
   traffic halted, Russia hits Kyiv river crossings in reply.
2. **Iran fires drones at a U.S. base in Bahrain** — radar at Sheikh Isa
   targeted; the attack was intercepted, no casualties.
3. **Xi, Trump & Putin to meet in Shenzhen** — first three-way summit,
   set for Thursday on the APEC sidelines.
4. **Tankers hit mines near Hormuz** — vessels struck and ablaze;
   Iran's foreign minister in talks in Oman.
5. **Europe plans a Rwanda returns hub** — five nations back a joint
   centre for rejected asylum seekers.

Sources: wire reports, 17 November 2026. The "dirty bomb" allegation
reported that day was left out on purpose — an unconfirmed intelligence
claim is not a fact to print as one.

## How the image was made

Five editorial illustrations (bridge, radar base, Shenzhen skyline,
tankers, Europe–Africa map) were generated as artwork — no text inside
them, so nothing can come out garbled. The infographic itself (date
banner, headlines, captions, footer) was composed with code (PIL),
so every word is crisp at any size. The illustrations are editorial
artwork, not photographs of the events.

## Running the entry

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png` and verifies the copy byte-for-byte. No network,
no randomness — both runs write identical bytes. The program also
refuses to finish if the copy ever exceeds the 1 MiB gate.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
sha256sum entry.png out/entry.png
```

## License

MIT — see [LICENSE](LICENSE).
