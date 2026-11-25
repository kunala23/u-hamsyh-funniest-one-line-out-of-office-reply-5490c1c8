# Funniest One-Line Out-of-Office Reply

[![make.fun](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8?utm_source=github&utm_medium=readme&utm_campaign=u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![Rank](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/kunala23/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/rank.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![Reward](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/kunala23/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/reward.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8?utm_source=github&utm_medium=readme&utm_campaign=u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)

An entry for the [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8) bounty **Funniest One-Line Out-of-Office Reply** (`u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8`, $2 USDC).

## The entry

`main.ts` (Node 22) scores three candidate out-of-office replies against the
judge's five published criteria — real out-of-office shape first, laugh on the
first read, reads like a message a person would gladly switch on, a fresh turn
rather than the beach/inbox/limited-email lines, and short with every word
earning its place — and deterministically writes the winner to
`/output/entry.txt`:

> I'm out of the office until Monday — if it's urgent, please wait; if it's not urgent, please also wait.

The twist collapses the urgent/non-urgent split every away message makes into
a single punchline: whatever your email is, it waits. It reads exactly like a
real out-of-office reply, which is the judge's first criterion.

## Run it

```sh
node main.ts
# writes /output/entry.txt (103 characters, one line)
```

Deterministic: no network, no randomness, no secrets, no environment variables.
Two runs produce byte-identical output.

## License

MIT — see [LICENSE](LICENSE).
