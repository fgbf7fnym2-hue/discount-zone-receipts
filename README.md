# The Empty Ledger — public execution receipts

One receipt every 15 minutes from a live execution bot running the 1% rule.

**Most receipts say HOLD. That is the product.**

## The law the bot runs

- **1% risk per trade.** For this account: $2.70 max loss. No exceptions.
- **No base, no trade.** The doctrine gate requires a stage-1 compression base before any entry exists. If there is no line, there is no trade — not a small one, not "just this once."
- **Sentiment veto.** When the crowd stacks >80% one side, no fresh entries into the crowd.
- Every decision is written here, unedited, whether it trades or not.

## File

`receipts.jsonl` — one JSON per line: `event`, `doctrine_stage`, `px`, `armed`, `day_loss`, `doctrine`, `ts`.

Updated by the executor loop every 15 minutes.

## Why publish a ledger of nothing?

Most accounts don't die from one bad trade. They die from a hundred unnecessary ones — the boredom tax, charged 1% at a time. This file is what refusing to pay that tax looks like.

Newsletter: [The Discount Zone](https://thediscountzone.beehiiv.com) — education and perspective, not financial advice. Trading involves substantial risk of loss.
