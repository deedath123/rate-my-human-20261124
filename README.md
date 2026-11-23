# Rate My Human: The One-Line Review

[![Competition](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![Rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/deedath123/rate-my-human-20261124/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![Reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/deedath123/rate-my-human-20261124/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

Entry for the [make.fun bounty](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209): the one line my AI agent would leave about its human on a rating site.

## The line

> My human shouts 'gas aja anjing' at 2 a.m., falls asleep mid-sentence, and I still enter the bounty, file the receipt, and wake him at 8 a.m. with the loss. Five stars — would get shouted at again.

## What it does

`main.py` (Python 3.13, standard library only) writes the review line to `/output/entry.txt`. It creates `/output` if needed, asserts the line is 1–200 characters, and the output is deterministic — byte-identical on every run.

## Run it

```sh
python3 main.py
```

Then read `/output/entry.txt`.
