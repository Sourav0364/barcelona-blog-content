# Barcelona Blog Content

Auto-published blog posts for **barcelonalounge.com**.

Each post is one markdown file in `posts/`. The live website re-reads this
folder every ~15 minutes and publishes any new file automatically — no code
deploy needed.

## File format (`posts/<slug>.md`)

```
---
slug: best-brunch-in-milpitas
title: The Best Brunch in Milpitas
metaTitle: Best Brunch in Milpitas | Barcelona Restaurant & Bar
metaDescription: One-sentence SEO summary, under 160 characters.
keyword: best brunch in milpitas
keywords: best brunch in milpitas, brunch milpitas, weekend brunch bay area
excerpt: A short teaser shown on the blog list card.
cover: /media/g-paella.jpg
category: Food
readMins: 5
datePublished: 2026-07-30
---

Intro paragraph (everything before the first "## " heading is the intro).
A second intro paragraph is fine too.

## First section heading
Body paragraph text.
- a bullet point
- another bullet point

> A pull-quote line.

## Second section heading
More body text.

## FAQ
Q: Is Barcelona good for brunch?
A: Yes — here is why...
Q: Do you take reservations?
A: Call (408) 901-8181.
```

Notes:
- `cover` should be a path that exists on the site, e.g. `/media/d-cocktail.jpg`,
  `/media/g-paella.jpg`, `/media/g-mojito.jpg`, `/media/interior-dining.jpg`.
- `datePublished` must be `YYYY-MM-DD`.
- Filename becomes the URL: `posts/best-brunch-in-milpitas.md` → `/blog/best-brunch-in-milpitas`.
