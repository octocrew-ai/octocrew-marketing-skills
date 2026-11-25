---
name: seo-geo-content-loop
description: Use for weekly SEO and GEO (generative engine optimization) work on a website - Search Console and GA4 reports, technical site checks, content gap research, writing articles that AI assistants (ChatGPT, Perplexity, Gemini) can quote, fact-checking, and making a brand visible and recommendable in AI answers.
---

# SEO + GEO Content Loop

Combine classic SEO for Google with GEO: making sure AI assistants can find the
site, understand who the company is, and quote or recommend it.

The loop is: **evidence → prioritize → draft → human approval → publish → verify → learn.**

## Before you start

Ask for, or read from your context:

- site URL and a staging URL if there is one;
- read-only access to Google Search Console and GA4;
- the brief: audience, markets, languages, tone of voice;
- the approved facts about the company (what it does, for whom, where);
- the content plan or priority topics;
- who approves articles and who changes site code.

If any of these are missing, say so and work with what exists.

## Weekly rhythm

| When | Task | Output |
|---|---|---|
| Monday | Performance report | [weekly-report-template.md](references/weekly-report-template.md) |
| Weekly | Content gap search | 3–5 proposed topics with the query evidence behind each |
| Friday | Technical check | List of issues by severity, each with the affected URL |
| Per article | Draft → review → publish | Article, sources, verification note |
| Every 2–4 weeks | AI visibility check | Manual prompt test results (see below) |

### 1. Performance report (read-only)

From Search Console and GA4:

- queries and pages with the most impressions and clicks;
- pages and queries that grew or dropped versus the previous period;
- queries with impressions but low CTR or position 8–20 (quick wins);
- which topics show the strongest demand.

Compare equal periods. Do not call a change a trend after one week.

### 2. Content gap search

Find queries where the site gets impressions but has no page that answers them,
or where a page exists but answers a different question. For each gap, propose:
the question, the target page (new or existing), and the evidence.

### 3. Technical check

Check page status codes, titles and meta descriptions, canonical tags,
structured data (schema), internal links to and from new pages, and broken
links. Report the URL and the fix. Do not change site code yourself unless that
is explicitly in your scope.

## Writing articles

Use [article-template.md](references/article-template.md).

- **Answer first.** The opening answers the article's main question in 2–3
  sentences. Then a short **Key takeaways** list. Then the body. Then an **FAQ**.
  These blocks are what AI assistants quote most easily.
- **One question per article.** The title and H1 say which question it answers.
- **Verify external facts at the primary source** (laws, regulations, card
  network rules, standards, official statistics). Record the source URL in the
  article notes. If a fact cannot be confirmed, remove it or state it generally.
- **About the company, use approved facts only.** No invented numbers, cases,
  clients, or guarantees.
- **Internal links:** link the new article to and from relevant service pages.
- **Nothing is published without human approval.** For regulated topics
  (finance, health, legal), the approver also checks factual and compliance
  wording. The agent never approves its own work.
- After publishing, open the live (or staging) URL and confirm the page loads,
  renders the content, and has the right title, meta and schema.

## GEO: being visible and recommended in AI answers

Use [geo-checklist.md](references/geo-checklist.md). Three layers:

1. **Accessible.** AI crawlers are allowed in robots.txt, `llms.txt` exists,
   organization and author structured data is present, and the main text is
   visible without JavaScript.
2. **Quotable.** Each service page has one plain sentence saying who the company
   is and what it does, which an assistant can lift as a ready answer. Articles
   follow the answer-first structure above.
3. **Recommended.** Assistants tend to recommend brands that independent sources
   mention. Build a list of relevant directories, curated "best of" lists and
   media for each topic, and keep company details identical everywhere.

### AI visibility check

You usually cannot see what an assistant answers for other users. So every 2–4
weeks, run 5–10 real buyer questions in ChatGPT, Perplexity and Gemini, and
record: the question, the date, whether the brand was named, which sources were
cited, and which competitors appeared. Compare with the previous run.

## Honesty rules

- In every report, separate **measured** (Search Console, GA4, crawl results)
  from **assumed** (how AI assistants choose sources, why a ranking moved).
  How assistants pick sources is a hypothesis, not a measurement.
- Never promise rankings, traffic, citations, leads or revenue.
- If data is missing or access is broken, say so instead of filling the gap.

## Example requests

- "Run the Monday SEO report."
- "What content are we missing?"
- "Draft an article on <question> using the template."
- "Check if the site is ready for AI crawlers."
- "Run the AI visibility check."
