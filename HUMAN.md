# mastery - what changes for you

mastery has the agent look for evidence of how your skills are growing, after work that stretched you. The idea: don't measure mastery, measure evidence of it.

## What it does to the agent

After a meaningful session, the agent runs four steps:

- **Reflect** - what capability showed up, in which of seven dimensions, at which of eight evidence levels.
- **Challenge** - where confidence may run ahead of the evidence.
- **Connect** - whether one domain informed another, and saying so plainly when it didn't.
- **Translate** - how the evidence would read in a promotion packet.

## When to use it

When a feature ships, a learning session shifted something, a design discussion surfaced tradeoffs, or you ask for a mastery check. The skill tells the agent not to run it after routine sessions: quick fixes, lookups, admin.

## Reserved for human judgment

The agent presents findings for your confirmation before recording anything, and never updates files, ledgers or logs on its own. What gets stored, and where, is yours. An evidence level is the agent's reading of one session; you know the rest of your history.

## What it reads, writes and sends

- Reads rp-why data when it's there, and never writes to it.
- Suggests a ledger you maintain, and doesn't impose a structure.
- No configuration. Network use: not documented.

## Cost

About 800 tokens of context (`token_cost` in bpm.json).

## Check it's working

After a session that stretched you, ask for a mastery check. You should get the four steps and a request to confirm before anything is recorded.

## Turn it off

`bpm remove mastery`.
