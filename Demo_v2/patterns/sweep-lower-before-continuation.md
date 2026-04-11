# Pattern: Sweep Lower Before Continuation

## Core Idea
Price dips below a key support to grab liquidity, then reclaims and continues higher.

## Description
In a bullish trend, dense liquidity clusters below price act as a magnet. The market sweeps into that zone to trigger stop-losses and liquidations, then reverses sharply. The sweep cleans the path for the real move higher. This pattern is more reliable when positioning data supports continuation and the sweep is fast with a clean reclaim.

---

## Required Conditions
- Bullish trend or bullish structure on the relevant timeframe
- Clear visible liquidity cluster below price on heatmap (1D or 3D minimum)
- Price sweeps below support and reclaims within the same candle or the next

## Supporting Signals
- Low TRL (low retail long participation)
- High OI delta (aggressive positioning expansion)
- CVD holds or rises during the sweep (buyers absorbing)
- Funding neutral or slightly positive
- Spot volume uptick on reclaim candle

## Invalid / Weak Version
- Weak when CVD drops hard during the sweep (real sellers, not a grab)
- Weak when funding is extremely high before the sweep (long squeeze, not a grab)
- Weak when there is no visible liquidity cluster on the heatmap
- Invalid when price sweeps below and accepts lower — closes multiple candles below support

---

## Failure Conditions
- Price loses the swept level and fails to reclaim within a few candles
- CVD continues falling after the sweep
- OI drops sharply after the sweep (position unwinding, not continuation)

## What Usually Happens Next
Price reclaims the swept support, consolidates briefly, then continues toward the next liquidity target above. The flush clears weak longs and shorts get caught in the reversal.

## What Confirms Entry
- Fast wick below support followed by a close above it
- CVD uptick during or after the sweep
- OI holding or increasing on the recovery candle

## What Cancels the Idea
- Price closes and accepts below the swept level
- CVD continues lower after the wick
- Multiple candles of sustained selling below the sweep zone

---

## Confidence Rating
- Pattern confidence: Medium
- Based on: 2 setups
- Outcome-validated: Partially (1 of 2 has a filled outcome)

---

## Related Setups
- [[setups/2026-04-09-btc-setup-01]] — structural example, outcome pending
- [[setups/2026-04-10-btc-setup-03]] ✓ — confirmed: swept 68k, rallied to 72.8k

## Related Concepts
- [[concepts/liquidation-heatmap]]
- [[concepts/open-interest]]
- [[concepts/cvd]]
- [[concepts/funding-rate]]

## Tags
#pattern #sweep-lower #continuation #liquidation-heatmap #bullish-trend
