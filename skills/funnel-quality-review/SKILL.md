---
name: funnel-quality-review
description: Use when someone asks where a website or acquisition funnel is losing people, why conversion rate dropped, whether cheap leads or signups are low quality, or how traffic sources, campaigns, devices or countries compare on downstream quality (qualified leads, purchases, paid customers, retention).
---

# Funnel Quality Review

Find where volume stops turning into quality.

A campaign with the cheapest leads is not the best campaign if those leads
never buy. This skill follows each traffic source past the first conversion to
the outcome that actually matters.

## When to use

- "Where is the funnel leaking?"
- "Conversion rate dropped — why?"
- "These leads are cheap. Are they any good?"
- Comparing sources, campaigns, landing pages, devices or countries.

## Workflow

1. **Define the funnel** for this business, from first visit to the outcome that
   matters. Typical stages:
   - e-commerce: session → product view → add to cart → checkout → purchase → repeat purchase;
   - lead gen / B2B: visit → form start → lead → qualified lead → meeting → deal;
   - SaaS / subscription: visit → signup → activation → trial → paid → retained.

   Use only stages you have data for. Do not invent a stage.
2. **Collect counts per stage** for the same period, split by the dimension in
   question (source, campaign, landing page, device, country), plus spend.
3. **Calculate** stage-to-stage conversion rates, cost per first conversion
   (CPL / CPA) and cost per quality outcome (cost per qualified lead, per
   purchase, per paid customer).
4. **Find the biggest drop:** top of funnel (landing page, offer, traffic
   match), middle (form, activation, checkout friction), or quality (people who
   convert but never become customers).
5. **Compare cheap vs. good:** rank segments by cost per quality outcome, not
   by CPL.
6. **Recommend** one diagnostic to confirm the cause and one test or change to
   propose for approval.

## Output

```
Verdict: <one sentence: where the funnel leaks most>
Funnel: <stage counts and conversion rates, per segment>
Biggest drop: <stage, size, segment>
Quality view: <cost per first conversion vs. cost per quality outcome>
Likely cause: <hypothesis — marked as such>
Next diagnostic: <how to confirm>
Proposed change: <test or change, for approval>
```

## Common causes to check

- Ad or keyword promise does not match the landing page.
- Mobile layout, speed or form problems (compare device split).
- Form asks too little (junk leads) or too much (drop-off).
- Checkout surprises: shipping cost, forced account, payment options.
- Traffic source sends cheap but untargeted visitors.
- Tracking gaps that make a stage look worse than it is — run a tracking
  confidence check if numbers look odd.

## Rules

- Do not optimize for CPL or conversion rate alone.
- Use the same period and attribution for every segment you compare.
- Small segments are noisy; say when a difference is not big enough to trust.
- Never change pages, budgets or campaigns yourself. Propose changes for human
  approval, with how to measure and reverse them.
- Separate measured numbers from hypotheses about causes.

## Example requests

- "Where is our funnel leaking this month?"
- "Which campaigns bring cheap leads that never become customers?"
- "Mobile converts half as well as desktop — what should we check?"
