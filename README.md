# content-strategist-Ominichannel-writer
Modular AI agent skills for full-funnel B2B content strategy, 30-day editorial architecture, and native omnichannel copywriting (LinkedIn, X, IG, Newsletter).
feat(skills): deploy content-strategy v4.0.0 and omnichannel-writer v3.0.0
# AI Content Strategy & Omnichannel Distribution Engine

A modular two-skill AI agent architecture designed to transform brand positioning documents into a 30-day, funnel-calibrated editorial calendar and native multi-platform content.

## Architecture Overview

This repository separates **strategic planning** from **platform execution** across two specialized agent skills:

1. **`.agents/skills/content-strategy.md` (v4.0.0) — The Strategist**
   - Reads brand foundation documents (`brand-context.md`) or conducts standalone diagnostic intake.
   - Maps ICP pain points across a 7-day weekly cadence calibrated to **TOFU (~20%)**, **MOFU (~65%)**, and **BOFU (~15%)** funnel stages.
   - Integrates **Two-Audience targeting**, **SLAY storytelling slots**, and **Hand-Raise DM triggers** (zero PDF lead-magnet dependency).
   - Enforces strict integrity guardrails (zero fabricated metrics) and includes a `VIDEO_PRODUCTION = PAUSED` toggle that automatically pairs `[FUTURE-REEL]` concepts with immediate Carousel or Single-Graphic substitutes.
   - Outputs a 30-day master blueprint to `outputs/content-strategy.md`.

2. **`.agents/skills/omnichannel-writer.md` (v3.0.0) — The Writer**
   - Translates any single planned day or core concept into four native platform formats simultaneously:
     - **LinkedIn** (Primary Anchor: Document Carousels & Structured Text Teardowns)
     - **X / Twitter** (High-Signal Threads)
     - **Instagram** (4:5 Swipeable Carousel Blueprints & Feed Captions)
     - **Email Newsletter** (Weekly Backstage Dispatches)
   - Enforces **Hook + Re-Hook** openers, **PAS** (*Problem → Agitate → Solution*) for tactical posts, and **SLAY** (*Story → Lesson → Actionable Advice → You*) for conviction posts.

## Directory Structure

```text
├── .agents/
│   ├── brand-context.md              # Single Source of Truth (positioning, ICP, voice, constraints)
│   └── skills/
│       ├── content-strategy.md       # Master 30-day strategic architect
│       └── omnichannel-writer.md     # 4-platform native copywriting engine
└── outputs/
    └── content-strategy.md           # Generated 30-day content blueprint
```

## Quick Start

1. **Generate your 30-day master strategy:**
   ```bash
   Run .agents/skills/content-strategy.md using my brand-context.md and generate outputs/content-strategy.md
   ```

2. **Draft native posts for any scheduled day:**
   ```bash
   Run .agents/skills/omnichannel-writer.md on Day 1 from outputs/content-strategy.md
   ```
