# positioning-offer-system

AgentSkill for Claude Code / OpenClaw that turns agency business context into a sharp positioning statement and landing-ready structure.

## What it does

One connected workflow:
1. **Context intake** — collects business, audience, client situation, and motivation across 20+ structured questions
2. **Competitive research** — parallel search for direct + adjacent competitors, builds comparison matrix
3. **Positioning** — forced-choice questions using real competitor names, produces a ≤30-word positioning statement
4. **Offer / UTP** — turns positioning into a concrete commercial offer with deliverables, timeline, and CTA
5. **Critique + quality gate** — scores 0–100, blocks weak results, enforces iteration
6. **Landing translation** — produces a 7-section landing skeleton with hero, mechanism, proof, objections, and CTA
7. **Output packaging** — saves result to a structured MD file

## Modes

| Mode | Use when |
|---|---|
| **Fast Track** (default) | Business is clear enough, need a result fast |
| **Deep Positioning** | Market angle or audience is still fuzzy |
| **Landing Copy Mode** | Positioning exists, need landing structure and copy |

## Quality rules
- No sentence over 20 words
- Positioning statement under 30 words
- No unverifiable adjectives (innovative, cutting-edge, world-class)
- Every claim is either true today or explicitly marked as a bet

## Install

Copy the skill folder into your OpenClaw workspace:

```
skills/
└── positioning-offer-system/
    ├── SKILL.md
    ├── references/
    └── assets/examples/
```

Then trigger with: *"Run positioning for [agency name]"* or *"Fast track positioning for my agency"*

## Structure

```
positioning-offer-system/
├── SKILL.md                          — main skill file
├── references/
│   ├── context-intake.md             — 20+ intake questions in 4 blocks
│   ├── positioning-workshop.md       — forced choices, positioning formula
│   ├── utp-offer-framework.md        — UTP formula, offer structure
│   ├── critique-and-logic-check.md   — 0-100 scoring, quality gate
│   ├── competitor-comparison.md      — parallel research, 8-dimension matrix
│   ├── landing-translation.md        — 7-section landing structure
│   ├── quality-rules.md              — hard constraints for all outputs
│   ├── anti-patterns.md              — what to never do
│   ├── output-template.md            — final MD output format
│   └── mode-guide.md                 — when to use which mode
└── assets/examples/
    ├── production-agency-example.md  — corporate production agency
    ├── agency-fast-track-example.md  — content agency fast track
    ├── agency-positioning-example.md — positioning options comparison
    └── landing-skeleton-example.md   — landing structure reference
```

## Inspiration

Inspired by [Gerstep/positioning-plugin](https://github.com/Gerstep/positioning-plugin) — a great structured positioning exercise for startups and teams.

Key differences in this skill:
- Extended for **service agencies** (not just product startups)
- Added **landing translation** — 7-section skeleton from hero to CTA
- Added **scoring gate** (0–100) — blocks weak positioning before it reaches the landing
- Added **deep context intake** — 20+ questions across 4 blocks (business, audience, situation, motivation)
- Added **anti-patterns** reference — what to never do
- Added **output template** — saves result to a structured MD file
- 4 worked examples including a corporate production agency pattern

## License

MIT
