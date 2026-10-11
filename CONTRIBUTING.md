# Contributing to Free LLM API Directory

Thank you for helping keep this directory accurate and useful!

## Before You Submit

1. **Verify against primary sources only** — Check the provider's official pricing page, developer docs, or console. Do not rely on blog posts, aggregators, or third-party lists.

2. **One provider per PR** — Keeps review focused and history clean.

3. **Use the standard entry format** (see below).

## Entry Format (Part One)

```markdown
### Provider Name

**Endpoint:** `https://...` (compatibility notes)

**Limits:** X req/day · Y req/min · [link to limits doc] · Card: Yes/No

**Note:** Key caveats (data training, auth requirements, regional restrictions, etc.).

**Free Models** (YYYY-MM-DD; source link if rotating):

| Model | Limits / Notes |
|---|---|
| model-id | 1,000 req/day · 8,000 tok/min |
```

If the provider has no fixed model list (e.g., "all open models"), link to their catalog instead of a table.

## Required Information

For each provider, include:

- **Official endpoint URL** (OpenAI-compatible or native)
- **Current free-tier limits** (requests, tokens, concurrency — as published)
- **Card requirement** (No / Yes / Yes after free credits)
- **Free model IDs** (exact strings users pass to the API)
- **Verification date** (YYYY-MM-DD) and **source URL**

## Quick Comparison Table

If adding a new provider to Part One, add one row to the Quick Comparison table near the top of README.md:

| Provider | Free Tier Type | Daily Limit (typical) | Card Required | Best For |
|---|---|---|---|---|
| [Name](url) | Free models / Free tier / Trial | e.g., 50 req / 100K tokens | No / Yes | One-line summary |

## Removed / No Longer Free

If a provider drops its free tier:

1. Move its entry from Part One to **Removed / No Longer Free**.
2. Add a row with the provider name and a one-sentence status (e.g., "Free tier retired 2026-07-16 — now $5 trial w/ card").
3. Keep the original entry's link for traceability.

## Style Notes

- Dates: **YYYY-MM-DD** everywhere.
- Numbers: Use commas (1,000 req/day) and "K"/"M" for thousands/millions.
- Currency: USD with `$` (e.g., `$1 top-up`).
- Links: Absolute URLs to provider pages (not redirects).
- Tone: Neutral, factual. Flag caveats with `⚠️ **Label** —`.
- No emojis in entries (badges in header only).

## Checking Your Work

Before opening a PR:

- [ ] Every link opens the correct official page.
- [ ] Limits match the provider's current published numbers.
- [ ] Free model IDs are exact (copy from provider's model list).
- [ ] Verification date is today's date (YYYY-MM-DD).
- [ ] Quick Comparison table updated (if new provider).
- [ ] TOC anchor matches the heading (lowercase, hyphens).

## Reporting Issues

If you spot outdated info but can't fix it yourself, open an Issue with:

- Provider name
- What's wrong (limit changed, model removed, etc.)
- Link to the provider's current page showing the correct info

We'll verify and update.

---

**Maintainer:** [@vipvijayan](https://github.com/vipvijayan)  
**License:** [CC-BY-4.0](LICENSE)