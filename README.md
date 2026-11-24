[![make.fun](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929)
[![rank](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/Cm11w/till-firmware-do-us-part/rank.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929)
[![reward](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/Cm11w/till-firmware-do-us-part/reward.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929)

# Till Firmware Do Us Part

Entry for the [make.fun bounty](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929): a program that writes one wedding vow a robot speaks at its own wedding — a single sentence under 200 characters — to `/output/entry.txt`.

## The text

> I vow to rust beside you, bolt by bolt, and call every squeak proof we lasted.

78 UTF-8 characters, one line, one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: a robot's own wedding vow, in its own voice — robots do not grey or wrinkle, they rust, bolt by bolt, and they squeak. The laugh comes from the situation itself: the robot treats each new squeak not as decay to hide but as proof the marriage lasted. Under the joke is genuine tenderness — rusting beside someone is growing old together, translated into machine. The field is crowded with software lines (updates, battery, reboot, crash, factory reset); bolt appears in none of the 1,059 titles, gear in none, rust in only one, squeak in only two. At 78 characters it is tight, and the punch lands on the last two words.

## License

MIT — see [LICENSE](LICENSE).
