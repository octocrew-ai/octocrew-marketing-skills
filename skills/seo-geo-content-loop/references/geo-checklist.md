# GEO checklist

Mark each item **OK**, **Fix**, or **Unknown**, with the URL or file checked.

## 1. Accessible

- [ ] `robots.txt` does not block the AI crawlers you want (for example GPTBot,
      OAI-SearchBot, ChatGPT-User, PerplexityBot, ClaudeBot, Google-Extended).
      Decide deliberately which to allow.
- [ ] `/llms.txt` exists and lists the key pages with one-line descriptions.
- [ ] `Organization` structured data on the home page: name, URL, logo,
      description, `sameAs` links to official profiles.
- [ ] `Article` structured data with a named author on articles; author pages exist.
- [ ] `FAQPage` structured data only where the page actually shows those Q&As.
- [ ] Main content is in the HTML response, not loaded only by JavaScript
      (check with `curl` or "view source").
- [ ] XML sitemap is current and submitted.

## 2. Quotable

- [ ] Each service page has one plain sentence: "<Company> is a <what> that
      <does what> for <whom>."
- [ ] The same description is used on the home page, About page and structured data.
- [ ] Articles open with a direct answer, then Key takeaways, then FAQ.
- [ ] Headings are phrased as the questions people ask.
- [ ] Facts and numbers on the page have visible sources.

## 3. Recommended

- [ ] List of relevant directories, curated "best of" lists, review sites and
      media per topic, with status: not listed / submitted / listed.
- [ ] Company name, description, URL, location and contacts are identical
      across all listings.
- [ ] Official profiles (LinkedIn, Crunchbase, G2 or industry equivalents) are
      complete and link back to the site.

## 4. AI visibility check log

| Date | Assistant | Question | Brand named? | Sources cited | Competitors named |
|---|---|---|---|---|---|

Results are a sample, not a measurement of all answers. Report them as such.
