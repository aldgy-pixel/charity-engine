---
name: charity-engine-ledger
description: Live capital + hours + revenue + charity-earmark ledger for the $10K-by-2027-10-04 goal. Update every session that touches Charity Engine work.
metadata: 
  node_type: memory
  type: project
  originSessionId: 369837ac-3497-430a-b8f9-8e675117180c
---

# Charity Engine Ledger

Tracks bets, capital, hours, revenue, and charity contributions toward the $10K-by-2027-10-04 goal. Sister file to [[project_charity_engine]].

## Running totals

| Metric | Current | Target |
|---|---|---|
| Donated to charity (after taxes) | $0 | $10,000 |
| Gross revenue earmarked | $0 | ~$28,571 |
| Capital deployed (cumulative) | $0 | starting <$1,000 + $400/mo reinvest |
| Hours invested (cumulative) | 0 | — |
| Days elapsed / remaining | 0 / 494 | 494 |
| Charity progress | 0% | 100% by 2027-10-04 |

## Schema for entries

Each bet is one block under `## Active bets`, moved to `## Closed bets` with a postmortem when it ends.

```
### YYYY-MM-DD — <bet name>
- Status: active | closed-won | closed-lost | killed
- Capital deployed: $X (cumulative for this bet)
- Hours spent: Z
- Revenue: $A
- Charity earmark: $C (after-tax × 50%)
- Kill criteria: <specific signal>
- Next action: <one concrete thing>
- Notes: <one line>
```

When a bet closes, append `- Postmortem: <one paragraph>` and update running totals at top.

## Active bets

### 2026-05-28 — Probe A: Wellness offer test
- Status: active
- Capital deployed: $0
- Hours spent: 0
- Revenue: $0
- Charity earmark: $0
- Kill criteria: 2026-06-11 reached with 0 closed calls at $1,497 AND <3 booked discoveries.
- Next action: Identify 50 warm-adjacent studios.
- Notes: Free 48hr mock as hook. Rebrand Pilates Punx booking flow as demo.

### 2026-05-28 — Probe B: Upwork benchmark
- Status: active
- Capital deployed: $0
- Hours spent: 0
- Revenue: $0
- Charity earmark: $0
- Kill criteria: 2026-06-11 reached with 0 contracts at ≥$45/hr AND <3 active interviews.
- Next action: Sprint 15 high-quality applications.
- Notes: Cash-in-hand path. Sales risk near zero.

## Closed bets

_(none yet)_

## Postmortems

_(none yet)_
