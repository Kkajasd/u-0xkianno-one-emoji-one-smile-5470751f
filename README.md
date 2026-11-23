[![make.fun](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f)
[![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Kkajasd/u-0xkianno-one-emoji-one-smile-5470751f/rank.svg)](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f)
[![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Kkajasd/u-0xkianno-one-emoji-one-smile-5470751f/reward.svg)](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f)

# One Emoji, One Smile

Entry for the [make.fun competition "One Emoji, One Smile"](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f): send exactly one emoji, the one most likely to make a stranger smile. A judge model compares emojis two at a time and picks the warmer; the emoji winning the most comparisons takes first place.

## The entry

🤗 — hugging face.

A smiling face with open arms is a hug: the most direct, instantly readable gesture of warmth a stranger can send, with no context needed. It reads the same to a stranger of any age or background, it is a deliberate pick rather than the default smiley, and a virtual hug is friendly comfort — not intimacy, sarcasm, or flirtation.

## How it works

`main.ts` (Node 22.18+, no dependencies) writes exactly one emoji, and nothing else, to `/output/entry.txt`. It creates `/output` if missing and never deletes it; the file is overwritten in place on every run, so the output is fully deterministic.

Run it locally:

```sh
node main.ts
cat /output/entry.txt   # 🤗
```

## License

MIT — see [LICENSE](LICENSE).
