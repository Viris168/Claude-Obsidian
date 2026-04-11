# Crypto Market Analysis Vault

A structured knowledge base for crypto market analysis, built in [Obsidian](https://obsidian.md). 
This vault stores market setups, repeating patterns, and outcomes so that analysis compounds over time rather than starting from scratch on every trade.

---

## What this is

Most traders analyze markets in isolation — one chart, one chat, one idea — and then forget what they learned. 
This vault solves that by treating every setup as a permanent record that feeds future decisions.

The core loop:

1. Record market conditions before the move
2. Run AI analysis using structured prompts
3. Save the result in the same file
4. Come back and fill the outcome
5. Extract lessons and build pattern files over time

Over weeks and months, the vault becomes a personalized library of tested market behaviors — not generic theory, but your own evidence.

---

## Key features

- **Structured setup files** — every market situation captured in a consistent format covering trend, structure, OI, funding, TRL, CVD, heatmap data, liquidity, and more
- **Pattern library** — repeatable market behaviors with required conditions, failure conditions, and confidence ratings based on confirmed setups
- **AI prompt system** — four purpose-built prompts for analysis, note expansion, setup validation, and general tasks
- **Outcome tracking and scoring** — every setup has fields for outcome quality, pattern match strength, and confidence calibration
- **Lessons aggregator** — all lessons from every setup collected in one file
- **Weekly review template** — structured reflection on signal performance and recurring mistakes
- **Single source of truth** — all vault logic lives in `CORE_RULES.md`, referenced by all other files without repetition

---

## Vault structure

```
/
├── QUICK_START.md              # Start here — task table and workflow guide
├── CORE_RULES.md               # All vault logic, language rules, output format
├── START_HERE.md               # Entry point for AI sessions
├── AI_CONTEXT.md               # Vault structure map for AI
├── index.md                    # Full vault map, grouped by type and tag
├── lessons.md                  # All lessons learned, aggregated
│
├── setups/                     # One file per market setup
│   └── YYYY-MM-DD-asset-setup-NN.md
│
├── patterns/                   # Repeated market behaviors (3+ setups to qualify)
│
├── concepts/                   # Definitions of key market terms
│   ├── open-interest.md
│   ├── funding-rate.md
│   ├── cvd.md
│   └── liquidation-heatmap.md
│
├── prompts/                    # AI instruction files
│   ├── crypto_ai_master_prompt.md
│   ├── master_ai_starter_prompt.md
│   ├── setup_pattern_expander_prompt.md
│   └── setup_matcher_validator_prompt.md
│
├── templates/                  # Blank forms for new files
│   ├── setup_template.md
│   ├── pattern_template.md
│   ├── weekly_review_template.md
│   ├── market_input_template.md
│   └── setup_review_template.md
│
└── reviews/                    # Weekly review files
    └── YYYY-WNN.md
```

---

## Signals tracked

Each setup captures the following data points:

| Category | Signals |
|----------|---------|
| Positioning | Open Interest (OI), OI delta, Funding rate, True Retail Longs (TRL) |
| Flow | CVD, Spot volume, Perp volume, Orderbook imbalance |
| Liquidity | 1D / 3D / 1W / 1M heatmap, Liquidity above, Liquidity below, Closest pool |
| Structure | Trend, Market structure, Key support / resistance |
| Context | Session, News, Exchange, Extra notes |

---

## How to use

### Getting started

1. Clone or download this repo
2. Open the folder as a vault in [Obsidian](https://obsidian.md)
3. Read `QUICK_START.md`

### Creating a new setup

1. Copy `templates/setup_template.md`
2. Name it `YYYY-MM-DD-asset-setup-NN.md` and place it in `setups/`
3. Fill in the Market Input section
4. Paste the contents of `prompts/crypto_ai_master_prompt.md` into your AI tool along with the setup
5. Save the AI analysis back into the same file

### Closing a setup (after the move)

1. Fill the Outcome section (After 1H, After 4H, After 24H)
2. Score it: Outcome Quality / Pattern Match Strength / Confidence vs Reality
3. Write one Lesson
4. Add the lesson to `lessons.md`
5. Update `index.md` with a ✓ if the outcome confirmed the thesis

### Creating a pattern

Only create a pattern after **at least 3 setups confirm the same behavior**. Use `templates/pattern_template.md` and link all confirming setups in the Related Setups section.

---

## AI prompt system

| Prompt | Purpose |
|--------|---------|
| `crypto_ai_master_prompt.md` | Full market analysis with historical comparison |
| `master_ai_starter_prompt.md` | Use when the task is unclear — routes to the right workflow |
| `setup_pattern_expander_prompt.md` | Turns short rough notes into full vault-style files |
| `setup_matcher_validator_prompt.md` | Validates whether a new setup matches an existing pattern |

All prompts enforce probability-based language and require historical comparison before drawing conclusions. Core rules are in `CORE_RULES.md`.

---

## Design principles

- **No absolute predictions** — every analysis uses probability-based language
- **History first** — new setups are always compared against old ones before concluding
- **No forced pattern matches** — a partial match is called a partial match, not a confirmation
- **Outcomes matter** — a setup without a filled outcome is structurally useful but not performance-validated
- **One source of truth** — rules live in one place and are not repeated across files

---

## Requirements

- [Obsidian](https://obsidian.md) (free) — for navigating the vault, following `[[wikilinks]]`, and using the graph view
- Any AI assistant — paste prompts and setup data directly into Claude, ChatGPT, or similar

No plugins required. The vault works with Obsidian's core features only.
