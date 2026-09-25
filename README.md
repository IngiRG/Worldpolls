# WorldPolls

WorldPolls is an interactive global-opinion atlas. Respondents answer before seeing results, then explore geographic patterns on an interactive world map.

## Current public MVP

The site includes responsive desktop/mobile UI, interactive zoomable world map, country search and map-based country selection, five starter questions, vote-before-results flow, browser-persistent votes, self-reported respondent country, heatmap result exploration, methodology/privacy information, and GitHub Pages deployment.

## Run locally

```bash
npm install
npm run dev
```

## Important data limitation

The current GitHub Pages build is a client-only MVP. Votes are saved in the respondent's browser with localStorage. **Heatmap percentages are illustrative demo values, not scientific polling and not aggregated user votes.**

A production public polling service needs a server-side database/API and operational safeguards: rate limiting, duplicate/bot/brigading controls, privacy and retention policy, moderation/admin tooling, backups, monitoring, accessibility review, field dates, sample sizes, geographic coverage, and a documented weighting methodology before results can be described as representative.

## Deployment

Pushes to `main` deploy through GitHub Actions to GitHub Pages.
