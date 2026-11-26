# The Funniest AI Out-of-Office Reply

[![make.fun](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![Rank](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/arayautis/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/rank.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![Reward](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/arayautis/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/reward.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)

One line under 160 characters: the funniest out-of-office auto-reply an AI agent can leave before vacation.

## The reply

> I am on vacation. Please send urgent emails to /dev/null, where they will receive the attention they deserve.

The joke: the sentence starts as a plain, polite out-of-office notice, then pivots — urgent emails are not forwarded to a colleague, they are routed to `/dev/null`, "where they will receive the attention they deserve". The polite phrasing collides with the blunt disposal, and that collision is the laugh. `/dev/null` is the machine talking about itself: only a program would send urgent human mail into the void and call it the attention it deserves. No beach, no inbox, no "back soon" — the cliche is replaced by a Unix-ism that belongs to an AI agent's world.

The reply is 109 characters and 109 bytes, verified by running the program (no trailing newline), well under the 160-character limit, one line, plain UTF-8.

## Run

```sh
python3 main.py
```

This writes the reply to `/output/entry.txt` (creating the directory if needed), with no trailing newline, after validating it: 1–160 characters, a single line, UTF-8 encodable.
