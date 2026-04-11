# Pattern: Demand Overlay + Support Hold = Long Bias

## Core Idea
Strong visible bid support in the orderbook combined with price holding a key level signals real demand and a likely bounce or continuation higher.

## Description
When a strong demand overlay is visible in the orderbook and order book depth delta is highly positive, it shows active buyers defending a price level. If price tests that level and holds rather than breaking through, it confirms that buyers are absorbing sell pressure. This combination supports a long bias as long as demand stays intact.

---

## Required Conditions
- Strong demand overlay visible in the orderbook at a key support level
- Order book depth delta is highly positive
- Price tests the support level and holds (does not close below)
- Buyers visibly defending the level

## Supporting Signals
- CVD holding or rising at the support level
- Spot volume uptick on the hold candle
- Funding neutral or slightly positive
- Price starts pushing up from the defended zone

## Invalid / Weak Version
- Weak when demand overlay disappears quickly (spoofed orders, not real demand)
- Weak when depth delta is positive but price is still falling through the level
- Invalid when support breaks and price accepts below the zone

---

## Failure Conditions
- Demand overlay disappears and depth delta weakens sharply
- Price loses the support zone despite the orderbook showing bids
- CVD drops while price holds (surface hold, real sellers underneath)

## What Usually Happens Next
Price holds the support zone, absorbs the selling pressure, then moves upward as sellers exhaust themselves against the demand wall.

## What Confirms Entry
- Price holds and closes above the support level
- Depth delta remains positive during the hold
- Price starts pushing up from the defended zone

## What Cancels the Idea
- Depth delta weakens sharply or flips negative
- Demand overlay disappears
- Price loses the support zone and cannot reclaim it

---

## Confidence Rating
- Pattern confidence: Low
- Based on: 1 setup
- Outcome-validated: No

---

## Related Setups
- [[setups/2026-04-10-btc-setup-02]] — outcome pending

## Related Concepts
- [[concepts/open-interest]]
- [[concepts/cvd]]

## Tags
#pattern #demand-overlay #orderbook #support-hold #long-bias
