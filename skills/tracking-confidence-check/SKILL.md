---
name: tracking-confidence-check
description: Use when someone asks whether CAC, CPA, ROAS, attribution, conversion counts, pixel or Conversions API data, delayed events, or tracking warnings are reliable enough to act on - especially before pausing, scaling or changing the budget of a paid campaign.
---

# Tracking Confidence Check

Decide whether performance numbers are ready to act on, or need caution.

Bad decisions in paid media often come from acting on incomplete data:
pausing a campaign whose conversions have not arrived yet, or scaling one whose
"wins" are duplicated events. This skill checks the data before anyone
touches a budget.

## When to use

- "Can we trust this CAC / ROAS?"
- "Should we pause / scale now or wait?"
- Platform numbers disagree with GA4, the CRM, the store or the backend.
- Tracking warnings, event match quality drops, or recent setup changes.
- Conversions with a delay (trials, subscriptions, offline or CRM sales).

## Workflow

1. **Collect** for the period in question: spend, conversions by event,
   CPA / CAC, ROAS or revenue, attribution window, and the same conversions
   from a second source (store, CRM, backend, GA4) if available.
2. **Run the checks** below and note each result.
3. **Assign confidence:** high, medium or low.
4. **Recommend a decision posture:** act, act cautiously, or wait and check.
   Any change itself goes to a human as an approval request.

## Checks

| Check | Warning sign |
|---|---|
| Data freshness | Period includes the last 1–3 days, or the conversion has a known delay (trial → paid, lead → sale) |
| Volume | Too few conversions to judge (as a rule of thumb, under ~30 per compared unit) |
| Source agreement | Platform conversions differ from the backend / CRM by more than ~20% |
| Duplicates | Pixel and server events both counted, or one purchase counted twice |
| Attribution window | Windows differ between the compared reports or periods |
| Recent changes | New pixel, CAPI, tag manager, domain, checkout or consent banner in the period |
| Event health | Platform warnings, falling event match quality, missing parameters (value, currency) |
| Seasonality / spikes | One day or one order drives most of the result |

## Confidence levels

- **High:** sources agree, enough volume, no recent changes, delays have passed.
  Safe to base a decision on.
- **Medium:** one warning sign. Decide cautiously, in small steps, and re-check.
- **Low:** two or more warning signs, or source disagreement. Do not change
  budgets or status on this data; fix or wait first.

## Output

```
Confidence: high | medium | low
Evidence: <what was checked and what it showed>
What could be wrong: <specific risks>
Decision posture: act | act cautiously | wait and check
Follow-up checks: <what to verify, by when>
```

## Rules

- Never change budgets, campaign status, bids or targeting yourself. Prepare an
  approval request with the current state, proposed change, reason, and how to
  reverse it.
- Never treat delayed conversions as final.
- If a field or source is missing, say it is missing. Do not estimate it silently.
- Separate measured numbers from your interpretation.

## Example requests

- "Can we act on this week's CAC or should we wait?"
- "Meta says ROAS 3.1, the store says 2.2. Which one do we use?"
- "Is it safe to scale campaign X today?"
