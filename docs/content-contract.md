# Content Contract

**Effective date:** 2026-07-22  
**Source reviewed in full:** `/Users/macbookprom42025/Downloads/deep-research-report (2).md`  
**Applies to:** public website copy, metadata, structured data, images, product mockups, forms, demos, and checkout surfaces  
**Default rule:** if a statement is not explicitly approved here and in `docs/claims-register.md`, it is not approved for production.

## 1. Binding product truth

### Current public state

| State | Decision | What the site may say |
|---|---|---|
| Prelaunch | **Yes** | The product is a prelaunch concept and the site is a preview. |
| Beta | **No** | Do not use “beta,” “early access,” or language implying a usable product until an operating build and enrollment terms are verified. |
| Human-assisted | **No representation approved** | Do not imply that staff, agents, brokers, or negotiators perform work for a buyer. |
| Fully operational | **No** | Do not use present-tense service or capability claims. |

The report is positioning and pricing advice. It is not proof that the product works, that the company has begun operations, or that any policy or commercial term has been adopted.

### Public name and category

- Use the configurable token `{BRAND_NAME}` until the business approves a public brand.
- The approved descriptor is **“buyer-side AI for car buying.”**
- Do not use **“Dealer AI”** as the public-facing brand, category, page title, metadata description, or navigation label by default. It sounds dealer-facing.
- The token `{BRAND_NAME}` itself must never render in production. A resolved, approved brand is a preview-launch blocker.

### Primary conversion

The only approved primary conversion is **waitlist registration**.

Joining the waitlist:

- may collect an email address and, only if separately approved, optional vehicle preferences;
- may subscribe the person only to clearly described product-launch communications;
- does not begin a vehicle search, produce a vehicle brief, contact a dealer, create a brokerage or agency relationship, reserve service, guarantee access, or take payment.

The following are not approved as the primary conversion: vehicle brief, product signup, paid purchase, consultation booking, dealer introduction, or negotiation request.

## 2. Exact header navigation

Use these items in this order. Do not add “Pricing,” “Reviews,” “Results,” “Partners,” “Dealers,” “Login,” or “Sign up” until the relevant experience and claims are approved.

| Position | Exact label | Target |
|---|---|---|
| Brand | `{BRAND_NAME}` | Page top |
| 1 | `Product concept` | `#product-concept` |
| 2 | `How it works` | `#how-it-works` |
| 3 | `FAQ` | `#faq` |
| 4, button | `Join the waitlist` | `#waitlist` |

The approved descriptor may sit next to or beneath the brand as: **“Buyer-side AI for car buying.”**

## 3. Exact approved hero contract

Only the following copy is approved above the fold.

**Eyebrow**  
`PRELAUNCH`

**Headline**  
`A clearer way to prepare for your next car purchase.`

**Subhead**  
`{BRAND_NAME} is a prelaunch buyer-side AI for car buying. We’re exploring tools to help buyers organize a vehicle search, compare dealer information, and prepare for negotiations.`

**Primary CTA**  
`Join the waitlist`

**Secondary CTA**  
`See the product concept`

**Reassurance copy**  
`Prelaunch preview. No purchase required. Features, pricing, and availability are not yet final.`

### Above-the-fold visual

A concept UI may appear only if the visual itself carries the persistent, legible label:

`Illustrative product concept — not a real dealer interaction.`

The visual must not contain a real dealer name or logo, a real person’s data, a fabricated “savings” result, a purported customer quote, a success rate, a dealer response represented as real, or an unlabeled fake transcript.

## 4. Homepage section order

The prelaunch homepage must use this order:

1. **Header** — exact navigation from section 2.
2. **Hero** — exact copy from section 3.
3. **Prelaunch status** — explain that this is a concept preview, not a currently available buying, brokerage, outreach, negotiation, or call-recording service.
4. **Product concept** — describe only the three approved exploratory outcomes below.
5. **How it works** — show a future-looking, three-step concept without implying that work begins today.
6. **Illustrative walkthrough** — optional; every artifact must use the required illustrative label.
7. **Waitlist form** — explain exactly what is collected and what joining does and does not do.
8. **FAQ** — use the approved answers in section 8.
9. **Final waitlist CTA** — repeat `Join the waitlist` and the prelaunch reassurance.
10. **Footer** — approved brand, contact route, privacy notice, terms if applicable, and prelaunch status. Do not list unsupported locations, affiliations, memberships, or partner logos.

There is no proof band, testimonial section, pricing section, dealer-logo strip, press strip, results counter, or checkout section in the approved prelaunch path.

## 5. Approved product-capability language

No capability is approved as presently operational. For the prelaunch preview, capability copy is limited to the exact exploratory framing below:

**Section heading**  
`What we’re exploring`

**Intro**  
`The product concept is designed around three parts of car-buying preparation. These features are not available in this preview and may change before launch.`

**Card 1 heading**  
`Organize the search`

**Card 1 body**  
`Bring vehicle preferences, budget, and search notes into one place.`

**Card 2 heading**  
`Compare dealer information`

**Card 2 body**  
`Review dealer-provided pricing and terms in a clearer, side-by-side format.`

**Card 3 heading**  
`Prepare for negotiation`

**Card 3 body**  
`Turn the information you have into questions and talking points for the purchase conversation.`

These statements describe a concept, not a live service. They do not approve or imply automated inventory access, dealer outreach, email sending, quote acquisition, negotiation on the user’s behalf, guaranteed out-the-door quotes, live listening, recording, transcription, real-time coaching, tactic detection, fee detection, financing advice, trade-in help, leasing help, interstate transactions, or human support.

### Exact “How it works” concept copy

**Heading**  
`How the concept works`

1. **`Share what you’re looking for`**  
   `Describe the vehicle and purchase preferences that matter to you.`
2. **`Organize the information`**  
   `Use one workspace to review the details you collect during the search.`
3. **`Prepare your questions`**  
   `Build a clearer list of items to confirm before deciding what to do next.`

Add immediately below:

`Concept only. The preview does not contact dealers, negotiate, record calls, provide brokerage services, or complete a vehicle purchase.`

## 6. Pricing and refund language

### Approved prelaunch pricing copy

`Pricing has not been announced. The prelaunch preview does not accept payment.`

### Approved prelaunch refund copy

`Because the preview does not accept payments, no refund policy applies at this stage. Any future paid offer and its cancellation or refund terms will be published before payment is accepted.`

No other price, discount, launch price, “standard” price, fee structure, value comparison, savings anchor, refund promise, cancellation promise, usage cap, or “no hidden fees” statement is approved.

The report’s suggested free tier, `$99`, `$149`, `$249`, and `$349` prices are recommendations only. They must not render in production, metadata, structured data, screenshots, or checkout until the business adopts an offer and the required operational, financial, and legal reviews are complete.

## 7. Negotiation artifacts: real versus illustrative

No real product or negotiation artifact was supplied with the report. Therefore, the current inventory is:

| Artifact | Current classification | Production rule |
|---|---|---|
| Vehicle brief | Illustrative only | Use fictional data and the required illustrative label. Do not call it generated, personalized, or real. |
| Dealer inbox or email thread | Illustrative only | Use fictional dealer identities and messages. Do not imply dealer participation or outreach. |
| Written quote or out-the-door comparison | Illustrative only | Use clearly fictional values; do not present savings or a market benchmark. |
| Live “Dealer said / Say this next” card | Illustrative only | Use fictional dialogue; do not imply listening, recording, transcription, or legal availability. |
| Transcript or call excerpt | Illustrative only | Label it; do not call it a recording or a real negotiation. |
| Tactic or fee alert | Illustrative only | Do not imply accurate detection, legal judgment, or financial advice. |
| Post-call summary | Illustrative only | Do not imply the call occurred or audio was retained. |
| Sample report or checklist | Illustrative only | A generic educational checklist is allowed if it makes no personalized, legal, or financial recommendation. |

Every illustrative artifact must show:

`Illustrative product concept — not a real dealer interaction.`

An artifact may be reclassified as real only after the owner records its provenance, obtains necessary permissions, removes personal and confidential information, confirms that no dealer or customer identity is misleadingly used, documents the relevant product version and date, and receives Product, Privacy, and Legal approval. A “real negotiation” also requires verified participant authorization and recording/usage review. Redaction alone is not sufficient.

## 8. Approved FAQ answers

Use these answers verbatim unless the claims register is formally updated.

### What is `{BRAND_NAME}`?

`{BRAND_NAME} is a prelaunch concept for buyer-side AI for car buying. The preview explains the product direction and collects waitlist registrations; it is not currently presented as a live vehicle-buying, brokerage, dealer-outreach, negotiation, or call-recording service.`

### What happens when I join the waitlist?

`You’ll register to receive product-launch updates. Joining does not start a vehicle search, contact a dealer, create a brokerage or agency relationship, guarantee access, reserve availability, or commit you to a purchase.`

### Can the product contact dealers or negotiate for me today?

`No. Those services are not available in this prelaunch preview. We will describe a capability as available only after it has been verified and the necessary business, privacy, and legal reviews are complete.`

### Does the product provide out-the-door quotes?

`Not in this preview. Any pricing or quote shown in a product concept is illustrative and is not a dealer offer.`

### Is live call coaching available?

`No. Live listening, recording, transcription, and coaching are not available in this preview. Any future call feature is subject to technical verification, an approved consent experience, a documented audio-handling policy, and qualified legal review.`

### Does the preview record or store audio?

`No. The prelaunch preview must not accept, record, or store call audio. No statement about a future product’s audio collection, storage, retention, deletion, or processing location has been approved.`

### How much will it cost?

`Pricing has not been announced. The prelaunch preview does not accept payment.`

### What is the refund policy?

`Because the preview does not accept payments, no refund policy applies at this stage. Any future paid offer and its cancellation or refund terms will be published before payment is accepted.`

### Will dealers contact me?

`The preview does not contact dealers or share your information with them. How any future dealer outreach or contact handling would work has not been finalized.`

### Can it help with leases, trade-ins, or out-of-state vehicles?

`Those service areas have not been announced. Do not rely on the preview as offering them.`

### Where will the product be available?

`Geographic availability has not been announced. Joining the waitlist does not guarantee availability in any location.`

### Does the site provide legal, financial, or vehicle-purchase advice?

`No. The prelaunch preview provides general product information only and is not a substitute for advice from a qualified professional.`

This last answer does not cure licensing, privacy, recording-consent, consumer-protection, or other legal issues. It is not a substitute for qualified review.

## 9. Copy that must not render in production

The following report language is not approved for the current site:

- `Buy the right car with buyer-side AI. It finds the car, handles the dealers, and coaches you live when it’s time to negotiate.`
- `Find the right car. Let AI handle the dealers. Negotiate like a pro on the call.`
- `Your buyer-side AI finds matching inventory, contacts dealers, handles the email back-and-forth, and coaches you live in real time when it’s time to negotiate price, fees, and terms.`
- `Buy smarter. Negotiate stronger.`
- `AI finds the car you want, handles the dealers for you, and coaches you live so you can negotiate with confidence instead of guessing.`
- `Flat fee per deal.`
- `No dealer kickbacks.`
- `No surprise add-ons.`
- `No hidden fees.`
- `If dealer outreach has not started, you can cancel and get a full refund.`
- `Find My Car`
- `See My Deal Plan`
- `Watch a Real Negotiation`
- `Compare My Options`
- `Start My Deal`
- `We find the right car`
- `We handle the dealer inbox`
- `We coach you live`
- `See real written dealer quotes before you step into the showroom.`
- `Negotiate the out-the-door price, not just the monthly payment.`
- `Know what to say when the dealer changes the numbers.`
- `Keep pressure on the deal without spending your weekend emailing dealerships.`
- any savings amount, percentage, range, “save thousands,” avoided-fee amount, or ROI calculation;
- any testimonial, review, star rating, customer count, deal count, email count, success rate, conversion rate, or satisfaction result;
- any press, partner, dealer, association, accreditation, or customer logo;
- any claim of dealer participation, dealer acceptance, dealer integration, dealer response, or geographic coverage;
- any claim that the company has no dealer affiliations, receives no dealer compensation, or takes no dealer kickbacks;
- any claim about recording legality, consent requirements, interstate calls, audio storage, audio retention, deletion, local/cloud processing, or security;
- any current capability not explicitly approved in section 5;
- the report’s competitor prices, market averages, FTC enforcement figures, conversion benchmarks, model costs, or transcription costs;
- the unresolved token `{BRAND_NAME}`.

“AI-powered,” “revolutionary AI,” “agentic,” and similar vague category language is also disallowed unless it is attached to a specific, verified capability. Do not use “Dealer AI” as public category language.

## 10. Evidence, sourcing, and approval rules

1. The report’s tokens such as `citeturn18view0...` are internal research references, not publishable citations and not evidence.
2. A report recommendation is not an adopted product fact, business policy, legal position, or proof item.
3. Any current capability claim requires a reproducible demonstration in the release candidate, dated test evidence, known limitations, and Product approval.
4. Any quantified outcome requires a written methodology defining sample, period, inclusion/exclusion rules, baseline, calculation, outlier treatment, and limitations; the underlying records must be auditable.
5. Any volatile public fact intended for publication must be re-sourced from a current primary source. The claims register must record the direct URL, retrieval date, owner, approval status, and required methodology before the fact is used.
6. Competitor marketing pages do not substantiate this company’s capabilities, business model, savings, independence, or policies.
7. Any legal or regulatory statement requires qualified review for the actual product flow and launch jurisdictions. This document does not provide legal advice.
8. If a claim has multiple applicable statuses, the strictest unresolved gate controls.

## 11. Change control

A statement moves to `approved` only when:

- its wording is exact;
- its evidence or decision is recorded in `docs/claims-register.md`;
- all named owners approve;
- any required methodology is complete;
- Legal/Privacy approval is obtained where flagged; and
- the content contract is updated in the same change.

Silence, a mockup, a roadmap item, a competitor precedent, an internal demo, or the absence of an objection is not approval.
