# Moovely

**Live: [moovely-umber.vercel.app](https://moovely-umber.vercel.app)**

Is the grass actually greener? Moovely compares any two places in the UK by what you would really have left each year after tax, rent and bills, not by headline salary.

## What it does

- **Compares 288 UK locations** side by side: take-home pay, rent, bills and the disposable income left over.
- **Calculates tax properly**: 2025/26 income tax and National Insurance, including Scotland's separate bands.
- **Personalises the result** for a young professional, a growing family or a downsizer working from home, with adjustable salary and home size.
- **Adds the things that matter when moving**: crime and school comparisons, an affordability gauge, and a one-line verdict.
- **Built to spread**: shareable comparisons with generated social images, popular-comparison pages, a blog and a sitemap for search.

## Stack

Next.js, React, TypeScript and Tailwind, deployed on Vercel. Location data and the tax logic are in [`src/data/locations.ts`](src/data/locations.ts) and [`src/lib/calculations.ts`](src/lib/calculations.ts).

```bash
npm install
npm run dev
```

Built by [James Harrop](https://jamesharrop.co), February 2026.
