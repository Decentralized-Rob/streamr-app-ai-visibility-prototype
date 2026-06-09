# StreamrTV visibility prototype

This is a lightweight prototype for a search-first and AI-readable StreamrTV product site.

It is not a redesign, campaign, or product-direction proposal. It is a structure showing how Streamr/StreamrTV could be easier for new users to find and understand using only official Streamr source material.

## Goal

Help people discover StreamrTV/Streamr through product-intent searches, not only through existing Streamr community channels.

## Working constraints

- Use official Streamr sources only.
- Do not invent product capabilities.
- Label roadmap/future features clearly.
- Keep Streamr Network and StreamrTV/Streamr product messaging separated.
- Optimize for both normal SEO and AI search extraction.

## Current hypothesis

Streamr Network has infrastructure visibility. StreamrTV/Streamr needs a clearer product discovery surface for creators, communities, secure video users, and people who do not already know Streamr.

## Prototype routes

- `/` — product discovery homepage
- `/what-is-streamr` — canonical product explainer
- `/how-it-works` — simple technical explanation
- `/for-creators` — creator and broadcaster use cases
- `/for-communities` — AMAs, events, community calls
- `/for-secure-meetings` — secure/private video direction
- `/powered-by-streamr-network` — bridge back to protocol/network
- `/faq` — AI-readable FAQ

## Official sources tracked

See `content/source-map.md`.

## Local setup

```bash
npm install
npm run dev
```

## Suggested contribution workflow

1. Build this separately as a prototype.
2. Share with Streamr team for review.
3. Ask whether there is a preferred repo/process.
4. Convert approved sections into issues, PRs, or production pages.
