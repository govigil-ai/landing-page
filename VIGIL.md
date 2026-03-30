# Vigil

## What it is
Competitive intelligence platform that monitors your competitors and turns what they're doing into specific marketing actions you should take.

## Core thesis
AI has commoditized software — every product in a category is converging to the same thing (Ramp vs Brex vs Rho vs Mercury are basically identical). The differentiator is now marketing and distribution, not product features. Marketing is the moat.

## How it works
Three layers:
1. **Data collection** — continuously scrape and monitor competitor activity
2. **Change detection** — diff everything over time, catch every move
3. **"So what" layer** — AI turns raw signals into specific, actionable marketing recommendations

It's not a dashboard. It's signal in, action out.

## Data sources (v1)
- **Website pages** — homepage, pricing, landing pages, positioning, structure changes
- **Search rankings** — organic keyword rankings by keyword and geographic location
- **Landing pages** — geo pages, industry pages, comparison pages, programmatic page patterns
- **API docs** — product capability changes, new features, changelogs
- **Social media** — LinkedIn company posts, Twitter/X, Reddit mentions
- **Review sites** — G2, Capterra reviews, sentiment, complaints (great for outbound ammo)

## Primary use cases
1. **Geo SEO** — identify cities/regions where competitors rank and you don't, generate page briefs to fill gaps
2. **Programmatic pages** — detect competitor page patterns (by industry, city, use case) and generate templates to match/beat them
3. **Cold outbound** — turn competitor weaknesses (from reviews, positioning gaps) into outbound messaging angles
4. **Positioning intelligence** — catch headline changes, pricing page updates, new comparison pages, and recommend responses

## Key differentiator
Most competitive intel tools (Crayon, Klue, Similarweb) are dashboards for executives. Vigil is for the people actually doing the marketing — demand gen, content, growth. The output is actions, not charts.

## Target customer
B2B SaaS companies in crowded categories where products have converged and marketing is the battleground.

## Name
Vigil — as in keeping watch. Always vigilant.

## Tech notes
- LinkedIn scraping: legal per hiQ v. LinkedIn ruling (public data, not CFAA violation). Use providers like Bright Data or ScrapIn rather than building own scraper. LinkedIn sued Proxycurl in Jan 2026, they shut down Jul 2026. Bright Data has positive legal precedent.
- Search ranking data: DataForSEO, Semrush, or Ahrefs APIs (~$50/mo+)
- Website scraping: custom scrapers on a schedule, diff for changes
- AI layer: processes signals and generates specific recommendations

## Landing page
- Name: Vigil
- Built with Framer (MCP plugin connected for AI editing)
- Dark theme, SaaS style
- Waitlist signup for early access
