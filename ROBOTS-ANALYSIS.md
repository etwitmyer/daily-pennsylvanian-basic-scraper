# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on [5/12/25]

```
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /
```

## Explanation


- **`User-agent: *`**  
  → This applies to **all bots/crawlers**, because `*` is a wildcard.

- **`Crawl-delay: 10`**  
  → This tells bots to **wait at least 10 seconds** between requests, to reduce server load.

- **`Allow: /`**  
  → This explicitly allows all bots to crawl **everything under the root directory** (i.e., the entire site), as long as they follow the crawl delay.

> So: **you’re allowed to scrape the site**, but ethically, your bot should wait 10 seconds between requests. Since we only scrape once a day, we’re good.

---
