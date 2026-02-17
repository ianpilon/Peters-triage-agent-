# Peter's Inbound Triage Agent

This repo contains a ready-to-use AI system prompt that acts as your personal triage assistant. It's designed to help you deal with the firehose of DMs, emails, texts, mentions, and intros you get every day — without burning hours deciding what deserves a response.

## How It Works

Copy the contents of **`triage-agent-prompt.md`** into the system prompt (or custom instructions) of your preferred AI tool — ChatGPT, Claude, or anything that supports system prompts.

Before you start, fill in the three placeholders near the top:

1. **North Star** — your long-term vision (12+ months)
2. **Active Bets** — the 2-3 projects you're pushing right now (1-3 months)
3. **This Week's Focus** — your specific deliverables for the week

Then paste in your inbound messages and let the agent sort them.

## What You Get Back

The agent classifies every message into one of four buckets:

| Label | Meaning | Your Action |
|-------|---------|-------------|
| RED | Respond today | Reply now — this is urgent and aligned with your goals |
| YELLOW | Batch within 48h | Queue it for your next response window |
| GREEN | Weekly review | Look at it when you do your weekly sweep |
| BLACK | Archive | Ignore — not worth your time |

It also suggests reply templates so you can respond quickly without drafting from scratch.

## Tips

- Update your goal stack weekly so the triage stays accurate.
- The agent defaults to "no" — that's by design. Your time is the scarce resource.
- If a certain type of low-value message keeps showing up, the agent will recommend a systemic fix (like an autoresponder or FAQ).
