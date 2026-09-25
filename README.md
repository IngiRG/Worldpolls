# WorldPolls

An interactive global opinion atlas: answer a question first, then explore how respondents around the world answered.

## Current MVP

- Interactive world map
- Vote-before-results flow
- Five starter questions across geopolitics, security, economics, institutions and migration
- Aggregate result visualizations
- Responsive desktop/mobile interface
- Clear demo-data and methodology labeling
- Question navigation

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

## Data note

All percentages and response counts currently included are **illustrative demo data, not scientific polling**. A public production version should disclose field dates, sample composition, weighting and geographic coverage, and should avoid describing a convenience sample as representative of “the world.”

## Next phase

The front-end is intentionally structured as an MVP. The next major step is a real backend (for example Postgres/Supabase) for polls and votes, followed by anonymous vote controls, country-level respondent breakdowns, moderation/admin tooling, privacy protections and deployment.
