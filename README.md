# StreamrTV Visibility Prototype

This is an unofficial community-built visibility prototype for StreamrTV.

It is not a redesign proposal, not an official Streamr project, and not a product-direction proposal. It is a practical starter site and page structure showing how StreamrTV can be easier for new users, creators, communities, and search/AI systems to find and understand.

The prototype uses official Streamr source material as the basis for product, protocol, naming, and network claims. It does not include the private source audit or source-tracking files.

## Disclaimer

This is an unofficial community contribution.

It is not an official Streamr project, not a request for Streamr to change its roadmap, and not a claim to represent the Streamr team.

The purpose of this repo is to explore a practical starter page structure that could make StreamrTV easier for new users, creators, communities, and search/AI systems to find and understand.

All product, protocol, naming, and network claims should be based on official Streamr source material. This repo should not use influencer commentary, Discord speculation, Reddit posts, market commentary, or third-party claims as source material.

Any audience paths in this prototype, such as creators, communities, or secure meeting users, should be treated as exploratory visibility paths unless directly supported by official Streamr material.

## Core idea

Streamr Network and StreamrTV should be treated as different web surfaces.

- **Streamr Network** explains the protocol, infrastructure, network roles, token mechanics, developers, node operators, sponsors, and decentralized data infrastructure.
- **StreamrTV** needs a clearer product-facing discovery layer for people who may not already understand Streamr, DATA, nodes, or decentralized data infrastructure.

The discovery problem is simple: people should be able to understand what StreamrTV is, who it may be useful for, how it connects to Streamr Network, and what can be used today without first needing deep background knowledge of the wider Streamr ecosystem.

## What this repo contains

```txt
content/
  streamrtv-visibility-brief.md
  page-plan.md
  github-note-to-team.md

src/app/
  page.tsx
  what-is-streamr/page.tsx
  how-it-works/page.tsx
  for-creators/page.tsx
  for-communities/page.tsx
  for-secure-meetings/page.tsx
  powered-by-streamr-network/page.tsx
  faq/page.tsx
```

The `content/` folder explains the visibility logic, page plan, and review framing.

The `src/app/` folder contains a small Next.js starter site structure showing how public-facing pages could be organized.

## Review path

For a quick review, start here:

1. `content/streamrtv-visibility-brief.md`
2. `content/page-plan.md`
3. `src/app/page.tsx`
4. `src/app/faq/page.tsx`
5. `content/github-note-to-team.md`

## What this is not

This is not an official Streamr repo.

This is not a product roadmap proposal.

This is not a generic SEO audit.

This is not based on influencer commentary, Reddit, Discord speculation, market claims, or third-party interpretations.

This repo does not include private source notes or private source-tracking files.

## What this is

This is a community contribution focused on practical visibility:

- clearer public-facing pages
- beginner-friendly explanations
- better separation between Streamr Network and StreamrTV
- more crawlable product context
- AI-readable FAQ structure
- source-grounded positioning
- clearer paths for creators, communities, and secure communication users where supported by official Streamr material

## Local development

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Then open:

```txt
http://localhost:3000
```

## Status

Early community prototype. Intended as a practical starting point for visibility structure, not a finished site.
