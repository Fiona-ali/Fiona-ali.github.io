# Week 7 — Break Your Own Site

**Site checked:** https://fiona-ali.github.io/  
**Check date:** 16 November 2026 (UTC)  
**Scope:** Fresh Chromium browser check, live interactions, outbound project links, Google PageSpeed Insights mobile run, and SEO/social-preview metadata.

## What I tried

- Opened the portfolio in a fresh browser context and followed the About, Work, Demo, Skills, and Contact navigation links. Each resolved to its matching section.
- Opened the GitHub profile, the Study Notes Coach case study, and the résumé PDF from the portfolio. All three destinations loaded.
- Submitted the demo form empty. Browser required-field validation blocked submission.
- Added a task containing angle brackets and punctuation. It displayed as text in the task list.
- Chose High priority, marked a task complete, removed it, and double-clicked Add. The task completed and removed correctly; the rapid double-click created one task, while the second empty submit was blocked by required-field validation.
- Removed the test entries afterward; the demo returned to zero open tasks.
- Inspected the contact and social links. I did not send email or messages.

## Fix-now findings and fixes

1. **Missing page description and social metadata.** The initial PageSpeed SEO score was 90 and flagged the missing meta description. I added a descriptive page title, meta description, canonical URL, Open Graph and Twitter metadata, and a portfolio-matched 1200 × 630 preview image.
2. **Search discovery support.** A Google query for `site:fiona-ali.github.io "Shaik Fiona Ali"` returned no results during this check. I added `robots.txt` and `sitemap.xml` to make the public pages easier for crawlers to discover. This does not guarantee when Google will index them.

## Speed check

[Google PageSpeed Insights mobile report](https://pagespeed.web.dev/analysis/https-fiona-ali-github-io/1ej47td696?form_factor=mobile) — run 16 November 2026 at 04:10 UTC, emulated Moto G Power, Lighthouse 13.6, slow 4G.

| Metric | Result |
| --- | ---: |
| Performance | 99 |
| Accessibility | 100 |
| Best Practices | 100 |
| SEO | 100 |
| First Contentful Paint | 1.5 s |
| Largest Contentful Paint | 1.5 s |
| Total Blocking Time | 0 ms |
| Cumulative Layout Shift | 0 |
| Speed Index | 2.8 s |

The earlier run scored 90 for SEO and identified the missing description. The later run scored 100 after metadata was deployed. Lab values can vary between runs and do not represent field data.

## Known limitations

- Google search indexing was not confirmed on the check date, even though crawler instructions and a sitemap are now published.
- PageSpeed still estimates about 700 ms of savings from render-blocking font requests. The site retains its custom fonts to preserve the visual design; the observed mobile Performance score is 99.
- This run used mobile emulation, not a new physical-phone test. Fiona previously confirmed the site works on her phone in the [Week 5 phone fix log](https://github.com/Fiona-ali/Fiona-ali.github.io/blob/main/open-it-on-your-phone-fix-log.md).
- Contact and social links were inspected, but I did not send messages or verify signed-in destinations.

## Review status

I completed a structured checklist review against the assignment criteria and found no additional must-fix defect in the tested paths. This is an assistant-run review record; it does **not** claim that a mentor or human peer reviewed the site. If FlyRank requires an external mentor/peer sign-off, that sign-off remains outstanding.
