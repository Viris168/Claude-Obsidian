# Quick Start

This vault is a crypto market analysis knowledge base.
It stores setups, patterns, and outcomes so analysis improves over time.

---

## What to do in under 1 minute

| Task | Read first | Use this prompt |
|------|-----------|-----------------|
| Analyze a new market setup | `CORE_RULES.md` | `prompts/crypto_ai_master_prompt.md` |
| Turn short notes into a full file | `CORE_RULES.md` | `prompts/setup_pattern_expander_prompt.md` |
| Check if a setup matches a pattern | `CORE_RULES.md` | `prompts/setup_matcher_validator_prompt.md` |
| Not sure what to do | — | `prompts/master_ai_starter_prompt.md` |

---

## How to create a new setup

1. Copy `templates/setup_template.md`
2. Name it: `YYYY-MM-DD-asset-setup-NN.md`
3. Fill the Market Input section
4. Run the master prompt for AI analysis
5. Save the output in the same file
6. Come back later and fill the Outcome section

---

## How to close a setup (after the move)

1. Open the setup file
2. Fill: After 1H, After 4H, After 24H
3. Fill: Was AI correct?
4. Write one Lesson
5. Score it: Outcome Quality / Pattern Match Strength / Confidence vs Reality
6. Add related links if missing

---

## How to create a new pattern

Only create a pattern after at least **3 setups confirm the same behavior**.

1. Copy `templates/pattern_template.md`
2. Name it with a short descriptive name
3. Link all confirming setups in the Related Setups section
4. Set the Confidence Rating honestly

---

## How to do a weekly review

1. Copy `templates/weekly_review_template.md`
2. Name it: `reviews/YYYY-WNN.md`
3. Fill it every Sunday

---

## Key files

- `CORE_RULES.md` — the single source of truth for all vault logic
- `index.md` — full map of the vault, grouped by tag
- `lessons.md` — all lessons learned across every setup
- `QUICK_START.md` — this file
