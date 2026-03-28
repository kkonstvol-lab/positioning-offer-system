---
name: positioning-offer-system
description: "Packages an agency or service offer into a landing-ready positioning workflow. Use when the task is to turn business context into clear positioning, sharpen the offer and UTP, compare against competitors, and convert the result into landing-page structure. Best for agency packaging, service-offer packaging, positioning-to-offer cleanup, and landing skeleton creation. Default mode: Fast Track."
---

# positioning-offer-system

One connected workflow: intake → positioning → offer → critique → competitors → landing.

Default to **Fast Track**. Switch modes only when clearly needed.

## Modes

### 1. Fast Track
Fast agency packaging into a landing draft. Use by default.
Deliver: positioning statement, UTP, offer structure, landing skeleton.

### 2. Deep Positioning
Use only when market angle, audience, or differentiation is still too fuzzy.
Deliver: market angle, audience definition, 2-3 positioning options, one chosen direction.

### 3. Landing Copy Mode
Use when positioning already exists and the job is converting it into landing blocks.
Deliver: landing narrative, section-by-section copy direction, proof and CTA logic.

See `references/mode-guide.md` for selection guidance.

## Workflow

### Step 0 — Read existing documents
If the user provides a website URL, PDF, or presentation: read it before asking questions.
Extract: current positioning, services, cases, stated differentiators, pricing, team.
Note what is weak, generic, or contradicted by the evidence.

### Step 1 — Context intake
Read `references/context-intake.md`.
Collect across 4 blocks: business, audience, client situation, motivation and barriers.
Do not ask everything at once — collect minimum viable input first, ask follow-ups if gaps remain.

Output: business context snapshot + strategic gaps + recommended mode.

### Step 2 — Competitive research
Read `references/competitor-comparison.md`.
Run two parallel web searches: direct competitors + adjacent competitors.
Find: common claims (= table stakes), white space, specific competitor names for Step 3.
Confirm findings with user before proceeding.

### Step 3 — Positioning
Read `references/positioning-workshop.md`.
Use real competitor names from Step 2 in forced-choice questions.
Define: market angle, target buyer, problem, mechanism, differentiation.
Produce: one positioning statement (≤30 words).

### Step 4 — Offer / UTP refinement
Read `references/utp-offer-framework.md`.
Turn positioning into a concrete commercial offer: UTP, deliverables, format, timeline, CTA.

### Step 5 — Critique and quality gate
Read `references/critique-and-logic-check.md`.
Run two passes: self-critique + logic check.
Score 0–100 across 5 dimensions.

**Gate:** if score < 70 → return to Step 3 or Step 4 and rewrite.
Maximum 2 loops. After 2 loops, output best version with explicit caveats.

### Step 6 — Landing translation
Read `references/landing-translation.md`.
Translate into 7-section landing skeleton: hero, problem, mechanism, offer, proof, objections, CTA.
Apply quality rules: ≤20 words per sentence, no unverifiable adjectives.

### Step 7 — Output packaging
Read `references/output-template.md`.
Save final result to: `projects/<agency-name>/positioning-output.md`
Include: positioning statement, UTP, offer, score, landing skeleton, first-draft-vs-final comparison.

## Quality rules (always apply)
Read `references/quality-rules.md` — apply to all outputs.

## Anti-patterns (always avoid)
Read `references/anti-patterns.md` before delivering any output.

## Examples
- `assets/examples/production-agency-example.md` — production / event agency (corporate clients, podcasts, events)
- `assets/examples/agency-fast-track-example.md` — content agency fast track
- `assets/examples/agency-positioning-example.md` — positioning options comparison
- `assets/examples/landing-skeleton-example.md` — landing structure reference

## Guardrails
- Do not generate positioning without competitive context.
- Do not accept the first draft as final — always run critique.
- If the offer is weak, say so directly and propose a stronger version.
- Prefer practical differentiation over abstract branding language.
- Claims must be either provably true or explicitly marked as bets.
- Default to **Fast Track** unless the user explicitly requests a different mode.
