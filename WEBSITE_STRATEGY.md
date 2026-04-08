# Whimble Growth-Led Website Strategy

## 1) Current Site Diagnostic (based on whimble.ca)

## Current major pages found
- Home (`/`)
- Individual Services
- Event Services
- Resource Hub
- Get Started (`/get-started`)
- About (`/about`)
- Trust & Safety (`/trust-and-safety`)
- FAQs (`/faqs`)
- Contact (`/contact`)
- Careers (`/careers`)

## What the current homepage is trying to do
- Introduce Whimble’s value proposition and service categories.
- Serve multiple audiences at once (individual clients, event organizers, caregivers, partners).
- Push users to “Get Started,” contact, newsletter, or service pages.

## Existing conversion paths
- Primary: **Get Started** page.
- Secondary: **Contact form**.
- Tertiary: **newsletter signup** and waitlist links.
- Event-specific conversion appears to route to external quote form.

## Main user journeys currently visible
1. Individual care seeker → Home → Services/Get Started → onboarding details.
2. Event organizer → Home/Trust page → external quote form.
3. Low-intent visitor → FAQ/Resource Hub/Contact → newsletter.
4. Existing client → “Existing Clients” portal.

## Growth issues (clear and direct)
- **Message mixing:** several audiences are addressed in the same blocks without clear routing.
- **Navigation complexity:** duplicate/open menu patterns and scattered links reduce clarity.
- **Conversion fragmentation:** multiple possible forms and destinations compete for attention.
- **Pricing trust appears, but not in conversion context:** users may still ask “what happens next?”
- **Trust content is strong but buried:** screening and safety info should be pulled earlier into funnel.
- **Waitlist logic is not obvious enough:** out-of-coverage users need clearer branch and nurture.
- **CTA hierarchy is inconsistent:** too many equal-weight actions in some areas.

## What is missing
- A single high-confidence funnel architecture.
- Explicit audience routing above the fold.
- Structured “awareness → trust → qualification → conversion” section order.
- Newsletter strategy as **secondary nurture channel** (not equal with “book now”).
- Caregiver recruiting path separated from client/service paths.

---

## 2) Proposed Website Architecture (growth-led)

## Sitemap (recommended)
- **Homepage** (`/`) — route users quickly + establish trust.
- **Individual Care** (`/care`) — high-intent consumer conversion page.
- **Event Services** (`/events`) — B2B quote conversion page.
- **Resources** (`/resources`) — SEO + nurture + newsletter.
- **About** (`/about`) — brand, credibility, standards, safety summary.
- **Contact / Get Started** (`/contact`) — routing hub + general fallback form.
- (Future) **Caregiver Careers** (`/careers`) — recruitment funnel.
- (Future) **City Pages** (`/ottawa`, `/toronto-west`) — location-specific SEO + conversion.

## Navigation hierarchy
- Primary nav: Individual Care, Event Services, Resources, About.
- Persistent top-right CTA: **Get Started**.
- Secondary footer nav: FAQs, Trust & Safety, Careers, Terms.

## CTA hierarchy
- **Primary CTA:** “Book a care consult” (individual) OR “Request event quote” (B2B context).
- **Secondary CTA:** “See how it works” / “Talk to team.”
- **Tertiary CTA:** “Join newsletter” (nurture only).

---

## 3) Homepage Blueprint (exact section order)

1. **Above the fold (Hero)**
   - Headline: “Care that actually cares.”
   - Subhead with who it’s for + what outcome.
   - Two primary actions:
     - Book a care consult
     - Plan an event
   - Immediate trust chips: vetted attendants, service area, response target.
   - **Why here:** first 5 seconds should answer “Is this for me?” and “Can I trust this?”

2. **Immediate post-hero: Route chooser card**
   - Buttons for: Individual care, Event services, Just researching.
   - **Why here:** removes confusion from mixed audiences and improves conversion rate.

3. **Trust block**
   - Screening standards, pricing transparency, service boundaries.
   - **Why here:** handles risk objections before form friction appears.

4. **How it works (4-step flow)**
   - Awareness → Trust → Qualification → Conversion.
   - **Why here:** lowers uncertainty and makes process feel simple.

5. **Service pathway cards (3 cards)**
   - Individual care (primary), Event services (secondary revenue), Resources (nurture).
   - **Why here:** creates obvious path depth.

6. **Social proof / proof of reliability**
   - Testimonials, partner logos (future), response metrics.
   - **Why here:** credibility before FAQ + final CTA.

7. **FAQ short list**
   - Coverage, emergency boundaries, onboarding logic.
   - **Why here:** pre-handles final objections.

8. **Footer CTA**
   - Get Started + Newsletter.

---

## 4) Form Strategy (exact placement + purpose)

## Form 1: Individual Care Consult (primary)
- **Where:** mid-page on `/care`, and linked from homepage hero + routing module.
- **Fields:** name, email, phone, city, support type, urgency, notes.
- **Why:** enough data to triage quickly and speed first human follow-up.
- **Growth purpose:** main revenue conversion for individual clients.

## Form 2: Event Quote Request
- **Where:** mid-page on `/events`.
- **Fields:** org, planner, contact, city, date, attendance, hours, support needs.
- **Why:** captures staffing scope for quoting.
- **Growth purpose:** B2B deal pipeline.

## Form 3: Newsletter (secondary)
- **Where:** `/resources` and footer mention.
- **Why:** capture low-intent visitors without distracting high-intent users.
- **Growth purpose:** nurture + future conversion + expansion demand sensing.

## Form 4: General Contact Fallback
- **Where:** `/contact`.
- **Why:** catch-all for partnerships, media, special requests.
- **Growth purpose:** no lead lost.

## Waitlist logic
- Ask city in service forms.
- If city outside service area:
  - show waitlist confirmation
  - offer newsletter opt-in
  - promise launch update for that city
- **Why:** preserves demand instead of bouncing users.

---

## 5) Page-by-page purpose summary

- **Homepage:** route + trust + clarity.
- **Care page:** convert individual demand.
- **Events page:** qualify and quote B2B demand.
- **Resources page:** educate and nurture undecided users.
- **About page:** reinforce credibility and brand values.
- **Contact page:** funnel router + fallback lead capture.

---

## 6) Brand and messaging direction

- Core line: **“Care that actually cares.”**
- Voice: warm, human, plain language, confidence without hype.
- Messaging formula:
  - Problem: care support is hard to coordinate.
  - Promise: vetted, transparent, respectful support.
  - Proof: screening standards + pricing clarity + lived-experience team.
  - Action: choose your path and submit the right form.

---

## 7) Walkthrough script you can present

1. “We simplified the website around three user intents: personal care, event care, and just researching.”
2. “Homepage now routes users immediately instead of forcing everyone through one mixed message.”
3. “Trust content moved up in the funnel to handle safety objections before users hit forms.”
4. “Forms are intent-specific, short, and tied to response workflows.”
5. “Newsletter is now secondary — a nurture lane, not a distraction from booking.”
6. “Out-of-area users are redirected into waitlist + nurture so we keep demand.”
7. “Every page now has a single clear purpose and conversion role.”

---

## 8) Next refinements (after prototype)

- Integrate actual CRM forms (HubSpot) + lead scoring.
- Add A/B tests:
  - hero headline variants
  - single CTA vs dual CTA in hero
  - trust block ordering
- Add analytics events:
  - route selection clicks
  - form starts/submits
  - waitlist conversions
- Add partner logos, verified reviews, and true client stories.
- Build location SEO pages and paid landing pages.
