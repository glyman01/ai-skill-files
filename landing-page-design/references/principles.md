# Conversion Principles, Testing, and Metrics

The strategic foundation for landing page decisions. Use this when explaining recommendations, evaluating tradeoffs, or planning optimization tests.

## The Blink Test

A landing page must communicate three things within 3-5 seconds of arrival:
1. **What** the offer is
2. **Why** it's valuable
3. **How** to get it (the action)

If any of these aren't clear from a glance, conversion suffers. When auditing or building, squint at the page (literally) and ask whether all three are obvious.

The blink test trumps cleverness. A boring headline that passes the blink test outperforms a clever one that fails it.

## Friction Reduction

Every conversion is a series of small decisions. Each one is a place where visitors can drop off. The job of optimization is to reduce friction at every step.

### Common sources of friction

- **Cognitive friction:** unclear copy, jargon, confusing layout
- **Visual friction:** cluttered design, competing CTAs, poor hierarchy
- **Trust friction:** missing privacy reassurance, no social proof, unprofessional design
- **Form friction:** too many fields, irrelevant questions, unclear field labels
- **Action friction:** vague CTA copy, hard-to-find button, unclear next step

Anything not directly serving the conversion is friction by default. The bar to keep something on the page is "this measurably helps conversion," not "this seems nice to have."

## Consistency With Traffic Source

The landing page should feel like a continuation of whatever brought the visitor there.

**This means matching:**
- The headline language used in the ad or email
- The image or video shown in promotion
- The specific offer and value props mentioned upstream
- The tone and visual style

**Why this matters:** Mismatch creates instant doubt. If the ad promised one thing and the page looks different, visitors question whether they're in the right place. That doubt costs conversions.

**Practical implication:** A single offer often needs multiple landing pages, one for each major traffic source, even if the underlying offer is identical.

## The One Page, One Goal Rule

Every landing page should have exactly one primary conversion goal. Multiple competing goals split attention and reduce conversion on all of them.

**This means:**
- One primary CTA (the form or the demo button or the download)
- Secondary CTAs are okay only if they serve the same goal (e.g., "Watch 2-min video" leads to the same form)
- Cross-promotion of other offers belongs on a thank-you page, not the landing page

If the user wants to promote multiple things, build multiple landing pages.

## Buyer's Journey Alignment

Different offers convert at different stages of the buyer's journey. Match the offer (and the form depth) to the stage.

### Top-of-funnel (Awareness)

The visitor is researching a problem, not evaluating solutions yet.

- **Offer types:** ebooks, guides, checklists, templates, blog subscriptions
- **Form depth:** Email only, or email + first name
- **Tone:** Educational, helpful, low-pressure

### Middle-of-funnel (Consideration)

The visitor is comparing approaches or solutions.

- **Offer types:** webinars, case studies, ROI calculators, comparison guides, assessments
- **Form depth:** Add company, role, company size
- **Tone:** Insight-driven, credibility-building

### Bottom-of-funnel (Decision)

The visitor is close to buying and evaluating specific options.

- **Offer types:** demos, free trials, consultations, pricing requests
- **Form depth:** Whatever sales needs to qualify (phone, team size, current solution, timeline, budget)
- **Tone:** Direct, value-focused, confident

A landing page that asks for top-of-funnel info but offers a bottom-of-funnel asset (or vice versa) creates mismatch and hurts conversion.

## Form Length Tradeoffs

The form is where the central tradeoff lives.

| Form Length | Lead Quantity | Lead Quality | When to Use |
|-------------|---------------|--------------|-------------|
| Short (1-3 fields) | High | Low | Top-of-funnel, list-building, broad reach |
| Medium (4-6 fields) | Medium | Medium | Middle-of-funnel, segmentation needed |
| Long (7+ fields) | Low | High | Bottom-of-funnel, sales handoff, qualification critical |

**The decision framework:**
- If priority is volume regardless of quality → minimize fields
- If priority is qualified leads → ask for what sales needs

**Progressive profiling:** If the platform supports it, ask for new info on each return visit instead of asking for everything upfront. This gets you long-form data without the conversion penalty.

## A/B Testing Priorities

Not all elements are equally worth testing. The biggest conversion gains usually come from these, in rough order of leverage:

### Highest leverage

1. **Offer itself** — Different offer types perform very differently. Test ebook vs. webinar, template vs. checklist, etc.
2. **Headline** — Single biggest copy element. Always worth testing.
3. **Hero image or video** — High-impact visual change. Test different visuals.
4. **Form length** — Adding or removing one field can shift conversion meaningfully.

### Medium leverage

5. **CTA button copy** — "Get Your Guide" vs. "Send Me the Guide" vs. "Download Now"
6. **Subheading** — Especially the value proposition framing
7. **Social proof type** — Testimonials vs. logos vs. stats

### Lower leverage (test last)

8. **Button color** — Often tested, rarely high-impact
9. **Button size** — Matters for mobile, less so for desktop
10. **Body copy length** — Short vs. long-form. Audience-dependent.

### Testing rules

- **Test one element at a time.** Otherwise you can't isolate what caused the change.
- **Reach statistical significance before declaring a winner.** Use a calculator, not gut feel.
- **Run tests long enough.** A week minimum, ideally two, to account for day-of-week variation.
- **Document what you learn.** Tests compound when you remember the lessons.

## Key Metrics

Five metrics matter most for landing page performance. Track all of them.

### 1. Page Views

The top of the funnel. Indicates promotion effectiveness and gives you the denominator for conversion rate.

**Watch for:** sudden drops (broken promotion, traffic source issue), source breakdowns (which channels are working), and the ratio between views and conversions.

### 2. View-to-Submission Rate (Conversion Rate)

The headline metric. Of the visitors who saw the page, what percent converted?

**Healthy benchmarks (rough):**
- Top-of-funnel: 15-25%+
- Middle-of-funnel: 5-15%
- Bottom-of-funnel: 2-10%

**Variables that affect this:**
- Traffic source (email converts higher than cold social, generally)
- Offer type and quality
- Form length
- Buyer journey stage match

### 3. New vs. Returning Conversion Rate

Split conversion rate into new visitors and returning visitors. They behave differently.

**Why it matters:** Top-of-funnel offers should pull strong new-visitor conversion. Bottom-of-funnel offers often have higher returning-visitor conversion (because returners know you).

### 4. Total Leads Generated

The bottom-line number. Are landing pages producing enough volume to support pipeline goals?

If conversion rate is good but lead volume is low, the issue is upstream (traffic). If conversion rate is poor, the issue is the page.

### 5. Video Engagement (if applicable)

If the page uses video, track:
- **Play rate** — what percent of visitors started the video
- **Completion rate** — what percent watched all the way through
- **Drop-off points** — where viewers leave (use heatmaps if available)

Use drop-off data to place CTAs just before common exit points.

## Mobile-Specific Considerations

Mobile users behave differently than desktop users. Optimization that works on desktop may fail on mobile.

**Mobile priorities:**
- Form must be reachable in 1-2 scrolls maximum
- Buttons must be 44px+ for tap accuracy
- Copy must be readable without zooming
- Page load under 3 seconds (ideally under 2)
- Video should autoplay muted with captions, not require a tap to start

**Test the mobile experience separately.** A page that converts at 25% on desktop and 5% on mobile is leaving most of its potential leads on the table.

## When to Stop Optimizing

There's a point of diminishing returns. After a few rounds of testing, additional optimizations may produce single-digit lifts that aren't worth the effort.

**Better uses of effort at that point:**
- Build more landing pages for different audiences or offers
- Improve traffic quality to existing pages
- Test new offer types entirely

A 20% lift from a new offer typically beats a 2% lift from a button color test.
