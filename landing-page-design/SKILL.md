---
name: landing-page-design
description: >
  Design, build, audit, and optimize landing pages for lead generation and conversion.
  Use this skill whenever the user wants to create a new landing page, rebuild a landing
  page, audit an existing landing page (URL, screenshot, mockup, or description), critique
  a landing page's conversion potential, write or rewrite landing page copy (headlines,
  subheadings, CTAs, value statements, form copy), or improve any single-purpose page
  intended to convert visitors into leads. Triggers on phrases like "landing page",
  "lead capture page", "conversion page", "lead gen page", "sign-up page", "opt-in page",
  "audit this page", "optimize my page", "improve this landing page", or any request
  involving headline, CTA, or form optimization for a focused conversion page. Default
  output is a full visual mockup in the user's preferred format (HTML, React, etc.) with
  strategic rationale. Do NOT use for general website redesigns, multi-page sites, blog
  posts, or content marketing pieces.
---

# Landing Page Design

Design, build, and optimize landing pages that convert visitors into leads.

A landing page is a **single-purpose page** built around one offer and one conversion action. It's not a homepage, a product page, or a content marketing piece. Everything on the page should serve the conversion goal, and anything that doesn't is friction.

## Before Starting

Read these reference files to load the strategic and tactical context:

- `references/anatomy.md` — the 10 essential components of a landing page and what each does
- `references/copywriting.md` — headline, subhead, CTA, value statement, and form copy patterns with examples
- `references/principles.md` — conversion psychology, A/B testing priorities, and key metrics
- `references/audit-rubric.md` — scoring framework for evaluating existing landing pages (read in audit mode)

## Modes of Operation

The skill has three modes. Pick the one that matches the user's request.

### Mode 1: Build a New Landing Page

Use when the user wants to create a landing page from scratch.

**Required inputs** (ask if missing):
- The **offer** (ebook, webinar, demo, free trial, discount, etc.)
- The **target audience** (who the page is speaking to)
- The **conversion goal** (what action the visitor takes)
- The **traffic source** (email, PPC, social, organic — affects messaging consistency)
- Output **format preference** (HTML, React/JSX, mockup spec, etc.)

**Optional but useful:**
- Brand colors, fonts, or existing design system
- Tone or voice (professional, playful, technical, etc.)
- Required compliance language
- Whether video will be included

**Process:**
1. Confirm inputs and clarify ambiguity before building
2. Draft the page structure following `references/anatomy.md`
3. Write copy following the patterns in `references/copywriting.md`
4. Build the visual mockup in the requested format
5. Provide a brief strategic rationale section explaining key decisions

### Mode 2: Audit an Existing Landing Page

Use when the user provides a URL, screenshot, mockup, code, or description of a current landing page and wants critique or optimization recommendations.

**Required inputs** (ask if missing):
- The page itself (URL, screenshot, code, or detailed description)
- The **offer** and **conversion goal**, so the audit can evaluate fit
- Whether the user wants a **critique only** or a **full rebuild**

**Process:**
1. Read `references/audit-rubric.md`
2. Score the page on each dimension (1-5)
3. Identify the highest-leverage issues (the 2-3 changes most likely to move conversion)
4. If the user wants a rebuild, proceed to Mode 3

**Output structure for audit:**

```
## Audit Summary
Overall conversion potential: [score]/50
Highest-leverage fixes: [top 2-3 issues, ranked]

## Component-by-Component Scoring
[Each component from the rubric, scored with reasoning]

## Recommended Changes
[Prioritized list with brief rationale for each]
```

### Mode 3: Rebuild from an Existing Page

Use when the user wants the existing page rebuilt, not just critiqued.

**Process:**
1. Run Mode 2 (audit) first to identify issues
2. Then run Mode 1 (build) using the audit findings as the optimization brief
3. The rebuilt page should preserve what's working and fix what's not
4. Note key changes from the original in the rationale section

## Output Requirements

The default output is a **full visual mockup** in the user's preferred format. If they haven't specified, ask before building.

**Common output formats:**
- **HTML/CSS** — single self-contained file, inline or `<style>` tag, no external dependencies unless requested
- **React/JSX** — single component, Tailwind for styling unless otherwise specified
- **Mockup spec** — annotated wireframe-style description if visual code isn't requested

**For all visual output:**
- The page must be functional as a mockup (real copy, not lorem ipsum)
- Form fields should be present and styled, even if non-functional
- CTAs should look like clickable buttons
- The page should pass the blink test when viewed (offer clear in 3-5 seconds)

**If the `frontend-design` skill is available**, read it for design execution patterns. This skill focuses on landing page strategy and copy. Use `frontend-design` for the visual craft.

## Quality Checklist Before Delivering

Run through this checklist before presenting any landing page output:

**Clarity & Messaging**
- [ ] Does it pass the blink test? (Offer clear within 3-5 seconds)
- [ ] Is the headline specific and benefit-driven?
- [ ] Does the subheading communicate the value proposition?
- [ ] Is copy scannable (short paragraphs, bullets where appropriate)?

**Conversion Elements**
- [ ] Is external navigation removed?
- [ ] Is there exactly one primary CTA?
- [ ] Is button copy specific and action-oriented (not "Submit")?
- [ ] Does form length match funnel stage?
- [ ] Is there a privacy reassurance or link near the form?
- [ ] Is social proof present and relevant to the offer?

**Visual & Structural**
- [ ] Does the visual hierarchy guide the eye toward the form/CTA?
- [ ] Is the image or video relevant to the offer (not generic stock)?
- [ ] Is the page mobile-friendly (if visual format)?
- [ ] Does the design align with brand if brand info was provided?

**Strategic Fit**
- [ ] Does the page match the traffic source's promise?
- [ ] Is form depth appropriate for the offer (lighter for top-of-funnel, deeper for bottom)?
- [ ] Is enough value communicated to justify the form fill?

If any item fails, fix before delivering.

## Anti-Patterns to Avoid

These show up frequently in landing pages and tank conversion. Watch for them:

- **"Submit" buttons** — vague, motivationless. Always replace with action-specific copy.
- **Multiple competing CTAs** — splits attention. One primary action per page.
- **Navigation menus** — exit paths that pull visitors away from the form.
- **Vague headlines** — "Welcome!" or "Learn More" tells visitors nothing about the offer.
- **Lorem ipsum or placeholder copy** in delivered output — the page is the deliverable.
- **Asking for too much information** at the top of the funnel — kills conversion rate.
- **No social proof** — visitors trust other customers more than your claims.
- **Mismatched imagery** — generic stock photos that don't reflect the offer.
- **Buried form** — if visitors have to scroll to find it, conversions drop.
- **Missing privacy reassurance** — increases form abandonment.

## When the User Pushes Back

Landing page optimization involves judgment calls. If the user disagrees with a recommendation:
- Ask what their data shows. They may have testing results that override defaults.
- Acknowledge that audience differences matter. What works generally may not work for their specific buyers.
- If they want to override a best practice, build what they ask for and note the tradeoff in the rationale section.

The goal is helping them ship a strong page, not winning an argument about theory.
