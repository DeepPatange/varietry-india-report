# Variety India indexing audit

An indexing audit of varietyindia.com: why articles aren't getting indexed by Google, and what to fix first.

## Files

- `variety-india-indexing-audit.html`: the report. Open it in a browser; it works offline except for fonts and ZIP reading.
- `variety-india-indexing-risk-by-url.csv`: all 3,869 articles with indexing risk, reasons, fix, word count, matching Variety.com original, and whether the article appears in Google results.

## What's in the report

- Search Console results: indexed vs not indexed, reasons, trend, and indexing by article length.
- Top issues ranked by impact, each with the number of pages affected and how to fix it.
- Evidence review that tests every issue against Search Console data.
- Sitemap audit (stale Cloudflare caching, false lastmod dates, robots.txt setup, Google News titles).
- A filterable list of every article with its risk and fix.

## Updating with new Search Console data

Open the report and drop Search Console exports (ZIP or CSV) on the "Update the report with new Search Console exports" box. The Search Console section, issue 1 and the article list rebuild from the new files. Files you add are stored only in your browser.

Data in the report: site crawl on Oct 21, 2026; Search Console Pages report to Oct 12, 2026; Performance export Apr 1 – Oct 18, 2026.
