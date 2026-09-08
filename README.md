# mastery

Reflective mastery engine for AI agents. Identifies evidence of developing practitioner mastery across domains through four behaviors: Reflect, Challenge, Connect, Translate.

## The Key Insight

Don't measure mastery. Measure evidence of mastery.

Mastery is not a self-assessment. It's not a feeling. It's a pattern that shows up in what you build, how you decide, and what you notice. This package gives your AI agent the structure to surface that evidence after meaningful work sessions - so you can track your development with precision instead of intuition.

## Who This Is For

Practitioners who want to track mastery development through AI-assisted work. Engineers, researchers, educators, designers - anyone who works with an AI agent and wants a structured record of how their capability is growing.

This is especially useful for:

- People who work across multiple domains and want to see how skills transfer
- Practitioners preparing for promotion or career transitions who need concrete evidence
- Anyone who suspects they're growing faster than their organization can see

## How It Works

After meaningful sessions (not routine ones), the agent runs four behaviors in sequence:

### Reflect

What capability was demonstrated? The agent identifies the specific skill, which of the seven mastery dimensions showed evidence, and where the observation lands on the eight-level evidence ladder.

### Challenge

Where does confidence exceed evidence? The agent pushes on edges - naming growth areas directly, flagging assumptions, and calibrating the gap between what the practitioner believes they can do and what the session actually demonstrated.

### Connect

Did knowledge from one domain influence another? Cross-domain synthesis is the signature of polymathic development. The agent surfaces these connections when they appear and stays honest when they don't.

### Translate

How would this evidence appear in a promotion packet? The agent converts observations into language that organizations recognize - scope, complexity, ambiguity navigated, and value delivered.

## The Evidence Ladder

Eight levels, from first encounter to teaching others:

| Level | Name | Description |
|---|---|---|
| 1 | Exposure | Encountered the concept |
| 2 | Understanding | Can explain it accurately |
| 3 | Application | Used it successfully |
| 4 | Repetition | Done it successfully across multiple situations |
| 5 | Adaptation | Can apply under unfamiliar conditions |
| 6 | Judgment | Knows when, why, and whether to use it |
| 7 | Contribution | Has improved how it's done |
| 8 | Transmission | Has helped others develop this capability |

The difference between levels is evidence, not time. You can jump from 2 to 6 in a single session if the evidence supports it.

## Seven Mastery Dimensions

Each skill is multidimensional. The agent evaluates evidence across:

- **Knowledge** - depth of understanding
- **Execution** - reliability of performance
- **Perception** - what you notice that others miss
- **Judgment** - how well you navigate tradeoffs
- **Adaptation** - handling novel situations
- **Contribution** - improving tools, practices, or shared knowledge
- **Transmission** - increasing others' capability

Not every session produces evidence in all seven. That's expected. The dimensions help the agent (and you) see which aspects of a skill are developing and which have gaps.

## Relationship to rp-why

`mastery` and `rp-why` are complementary, not coupled. They look at the same sessions through different lenses:

- **rp-why** tracks cost, routing, and token economics - the operational side of AI-assisted work
- **mastery** tracks capability development - the human side of AI-assisted work

`mastery` can read rp-why data to enrich its observations (e.g., "this session had high token spend but also produced level 6 evidence in a new domain - the exploration cost was justified"). It never writes to rp-why data.

Neither package depends on the other. They work well together but function independently.

## Installation

```
bpm install mastery
```

## Configuration

No configuration required. The convention activates based on session characteristics and practitioner requests.

The agent will always present findings for confirmation before recording anything. You control what gets stored and where.

## License

MIT
