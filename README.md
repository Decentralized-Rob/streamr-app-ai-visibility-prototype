# Streamr App AI Visibility Prototype

A community-built AISEO and automation prototype for improving how Streamr App can be discovered, understood, and explained across search engines, AI answer systems, and new-user entry points.

The current Streamr product surface is security-first, serverless video communication built on Streamr Network. This repo explores the missing middle layer around that product: crawlable explanations, structured FAQs, clear user-intent pages, and reusable content patterns that help humans and AI systems understand the product without first needing to understand the whole protocol stack.

## Project context

Streamr has deep protocol and infrastructure material. Streamr App has a different visibility challenge: a new visitor should be able to understand the product surface before learning DATA, Operators, Sponsorships, token mechanics, or decentralized real-time data infrastructure.

This prototype treats public product content as structured product knowledge. The same content has to serve several readers at once:

- new users looking for a simple explanation
- privacy-conscious teams evaluating secure communication tools
- communities and event hosts exploring live or multi-speaker formats
- search engines crawling the product surface
- AI systems extracting short answers
- future automation workflows that need consistent, source-grounded content blocks

## AISEO and automation angle

This is not a brochure-site exercise. The visible pages are only the first layer.

The deeper work is organizing Streamr App knowledge so it can be parsed, reused, checked, expanded, and surfaced more reliably. A practical AISEO layer should improve:

- entity clarity
- user-intent page structure
- extractable FAQ answers
- product/protocol separation
- beginner-safe explanations
- source-grounded claim discipline
- reusable content blocks
- future metadata and sitemap logic
- future internal-linking suggestions
- repeatable content review workflows

## Scope

This prototype is built around four practical goals:

1. Make Streamr App easier to understand from a first visit.
2. Keep product-facing explanations separate from protocol-facing explanations.
3. Create page structures that search engines and AI answer systems can parse cleanly.
4. Establish reusable content patterns that can support future automation.

The repo keeps the current file and route names for continuity, but the visible framing now uses Streamr App as the primary product name. References to StreamrTV should be treated as historical or transitional context unless the team prefers otherwise.

## Source rule

Product, protocol, naming, and network claims should be grounded in official Streamr material.

Audience paths such as secure meeting users, communities, creators, and multi-speaker broadcasts are treated as visibility paths for this prototype. They should stay aligned with what official Streamr material supports.

Private source notes and source-tracking files are kept outside this public repo.

## Repo structure

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

The `content/` folder explains the visibility logic, AISEO framing, and page plan.

The `src/app/` folder contains a small Next.js prototype showing how public-facing content could be structured.

## Review path

For a quick review, start here:

1. `content/streamrtv-visibility-brief.md`
2. `content/page-plan.md`
3. `src/app/page.tsx`
4. `src/app/faq/page.tsx`
5. `content/github-note-to-team.md`

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

Early community prototype. The current focus is AI visibility structure, automation-ready content patterns, clarity, and discoverability.
