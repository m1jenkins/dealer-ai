# Claims Register

**Register date:** 2026-07-22  
**Current launch mode:** Prelaunch preview  
**Source report:** `/Users/macbookprom42025/Downloads/deep-research-report (2).md`

This register is the approval ledger for website statements. The report’s internal citation tokens are not source URLs and are not publishable evidence. A claim not listed as `approved` is prohibited from production copy, metadata, structured data, visuals, form confirmations, demos, and checkout.

## Status definitions

| Status | Meaning |
|---|---|
| `approved` | The exact prelaunch wording may be used, provided the site behavior remains consistent with it. |
| `evidence-required` | Objective product or outcome evidence is missing. Do not publish until the method and evidence are approved. |
| `business-decision-required` | The company has not adopted the offer, policy, scope, or operating decision. |
| `legal-review-required` | Qualified counsel and, where applicable, Privacy review must assess the actual flow and jurisdictions. This register does not provide legal advice. |
| `remove` | Must not appear in the current production site. A future reconsideration requires a new, narrower claim and a fresh review. |

If more than one gate applies, the named status is the controlling gate and the “Requirement” field records the additional work.

## A. Approved prelaunch statements

| ID | Exact statement | Status | Source URL | Retrieved | Owner | Required methodology / condition |
|---|---|---|---|---|---|---|
| A-001 | `{BRAND_NAME} is a prelaunch buyer-side AI for car buying.` | approved | Not applicable — company-owned positioning | — | Product + Brand | Resolve `{BRAND_NAME}` before production; do not imply availability. |
| A-002 | `A clearer way to prepare for your next car purchase.` | approved | Not applicable — approved prelaunch copy | — | Product + Brand | Use only with the prelaunch eyebrow, subhead, and reassurance in the content contract. |
| A-003 | `We’re exploring tools to help buyers organize a vehicle search, compare dealer information, and prepare for negotiations.` | approved | Not applicable — product-concept framing | — | Product | Must remain future-looking; no current capability implication. |
| A-004 | `Join the waitlist` | approved | Not applicable — conversion decision | — | Growth + Product | Form must perform waitlist registration only and make the communication consent clear. |
| A-005 | `See the product concept` | approved | Not applicable — navigation copy | — | Product | Destination must label unavailable features and illustrative artifacts. |
| A-006 | `Prelaunch preview. No purchase required. Features, pricing, and availability are not yet final.` | approved | Not applicable — launch-state disclosure | — | Product | Site must not take payment or guarantee access/availability. |
| A-007 | `Illustrative product concept — not a real dealer interaction.` | approved | Not applicable — artifact disclosure | — | Product + Brand | Must be persistent and legible on every concept artifact. |
| A-008 | `Pricing has not been announced. The prelaunch preview does not accept payment.` | approved | Not applicable — prelaunch commercial decision | — | Product + Finance | Verify no payment or checkout path is active. |
| A-009 | `Because the preview does not accept payments, no refund policy applies at this stage. Any future paid offer and its cancellation or refund terms will be published before payment is accepted.` | approved | Not applicable — prelaunch commercial decision | — | Product + Finance | Must not be shown on a payment-taking experience. Future terms require Legal review. |
| A-010 | `The prelaunch preview must not accept, record, or store call audio.` | approved | Not applicable — preview product constraint | — | Engineering + Privacy | Release verification must confirm no audio input, recorder, upload, or retention path. |
| A-011 | `The preview does not contact dealers or share your information with them.` | approved | Not applicable — preview product constraint | — | Engineering + Privacy | Verify form integrations and automations; no dealer recipient or data transfer may exist. |
| A-012 | `The prelaunch preview provides general product information only and is not a substitute for advice from a qualified professional.` | approved | Not applicable — scope statement | — | Product | Does not replace qualified review or cure licensing/compliance issues. |

## B. Headlines, subheads, reassurance, and CTAs proposed by the report

| ID | Proposed statement | Status | Source URL | Retrieved | Owner | Required methodology / condition |
|---|---|---|---|---|---|---|
| C-001 | `Buy the right car with buyer-side AI. It finds the car, handles the dealers, and coaches you live when it’s time to negotiate.` | remove | None — report token is not evidence | — | Product | Decompose into separately verifiable claims after launch; dealer handling and call coaching also require Legal review. |
| C-002 | `Find the right car. Let AI handle the dealers. Negotiate like a pro on the call.` | remove | None — report token is not evidence | — | Product | Implies operational search, representation, and call coaching. |
| C-003 | `Your buyer-side AI finds matching inventory, contacts dealers, handles the email back-and-forth, and coaches you live in real time when it’s time to negotiate price, fees, and terms.` | remove | None — report token is not evidence | — | Product + Legal | Requires feature-by-feature demonstrations plus outreach, licensing, recording, privacy, and advice review. |
| C-004 | `Buy smarter. Negotiate stronger.` | remove | None — proposed copy only | — | Brand + Product | Not approved for prelaunch because surrounding report copy turns it into an operational outcome promise. |
| C-005 | `AI finds the car you want, handles the dealers for you, and coaches you live so you can negotiate with confidence instead of guessing.` | remove | None — report token is not evidence | — | Product + Legal | Requires demonstrated operation and qualified review. |
| C-006 | `Flat fee per deal.` | business-decision-required | None — recommendation only | — | Product + Finance | Adopt the offer, define “deal,” billing trigger, inclusions, taxes, and exceptions; then obtain Legal review. |
| C-007 | `No dealer kickbacks.` | remove | None — no company compensation evidence | — | Executive + Finance + Legal | Prohibited by instruction. A future independence statement needs complete revenue/affiliate/referral documentation and new approval. |
| C-008 | `No surprise add-ons.` | remove | None — ambiguous absolute | — | Product + Legal | Could be interpreted as controlling dealer conduct; rewrite around what verified software displays. |
| C-009 | `Find My Car` | remove | None — proposed CTA only | — | Product | Implies an available search service. |
| C-010 | `Watch a Real Negotiation` | remove | None — no real artifact supplied | — | Product + Legal + Privacy | Requires a genuine, authorized, provenance-verified artifact; recording and usage review is mandatory. |
| C-011 | `See My Deal Plan` | remove | None — proposed CTA only | — | Product | Implies a generated/personalized deliverable. |
| C-012 | `Compare My Options` | remove | None — proposed CTA only | — | Product | Implies an operational comparison workflow. |
| C-013 | `Start My Deal` | remove | None — proposed CTA only | — | Product + Legal | Implies service commencement and potentially an agency/broker relationship. |
| C-014 | `Get Started` | remove | None — proposed CTA only | — | Product | Ambiguous and inconsistent with the waitlist-only conversion. |
| C-015 | `No hidden fees. Flat price per deal.` | remove | None — no adopted offer | — | Finance + Legal | “No hidden fees” is an unsupported absolute; the fee structure is undecided. |
| C-016 | `If dealer outreach has not started, you can cancel and get a full refund.` | legal-review-required | None — competitor pattern/recommendation only | — | Finance + Operations + Legal | Adopt cancellation trigger, evidence of “started,” timing, refund method, exceptions, statutory rights, and jurisdictional terms. |
| C-017 | `AI Car Finder and Dealer Negotiator` | remove | None — proposed feature heading only | — | Product + Legal | Implies operational inventory search, outreach, representation, and negotiation. |
| C-018 | `Live Negotiation Coach` | remove | None — proposed feature heading only | — | Product + Legal | Implies an operational call feature; technical, recording, privacy, advice, and jurisdiction gates are unresolved. |
| C-019 | `Tell us the car` | remove | None — proposed step heading only | — | Product | In the report’s flow this begins an operational vehicle-search service; use the approved concept wording instead. |
| C-020 | `Let the AI run the deal` | remove | None — unsupported and overbroad | — | Product + Legal | “Run the deal” implies operational authority, representation, and control. |
| C-021 | `Use live coaching to close` | remove | None — proposed step heading only | — | Product + Legal | Implies an operational call coach and an outcome role in closing a purchase. |
| C-022 | `We find the right car` | remove | None — proposed feature heading only | — | Product | “Right” is subjective and the search capability is unverified. |
| C-023 | `We handle the dealer inbox` | remove | None — proposed feature heading only | — | Product + Legal | Dealer communications and user authorization are unverified and unreviewed. |
| C-024 | `We coach you live` | remove | None — proposed feature heading only | — | Product + Legal | Live listening/transcription/coaching is unavailable and unreviewed. |
| C-025 | `See real written dealer quotes before you step into the showroom.` | remove | None — no product or artifact evidence | — | Product + Legal | Requires verified quote acquisition, provenance, authorization, and accurate definition of “quote.” |
| C-026 | `Negotiate the out-the-door price, not just the monthly payment.` | remove | None — proposed current capability language | — | Product + Legal | Requires verified capability, OTD methodology, and negotiation/licensing review. |
| C-027 | `Know what to say when the dealer changes the numbers.` | remove | None — proposed current capability/outcome language | — | Product + Legal | Implies reliable real-time detection and advice. |
| C-028 | `Keep pressure on the deal without spending your weekend emailing dealerships.` | remove | None — proposed current capability/outcome language | — | Product + Legal | Implies automated outreach, follow-up, and a time-saving outcome without evidence. |

## C. Product capability claims

The “Source URL” is intentionally blank for product claims. Public web sources and competitor pages cannot establish that this product performs a function.

| ID | Capability claim | Status | Source URL | Retrieved | Owner | Required methodology / condition |
|---|---|---|---|---|---|---|
| P-001 | Finds matching vehicle inventory | evidence-required | None — first-party build evidence required | — | Product + Engineering | Reproducible test across defined sources, freshness, coverage, failure modes, and disclosure of limitations. |
| P-002 | Surfaces real matches and dealer options | evidence-required | None — first-party build evidence required | — | Product + Engineering | Define “real,” verify VIN/listing freshness and deduplication, and document source permissions. |
| P-003 | Sources alternates | evidence-required | None — first-party build evidence required | — | Product + Engineering | Test matching criteria and explain ranking/alternates. |
| P-004 | Contacts dealers for the buyer | legal-review-required | None — first-party build and legal review required | — | Product + Operations + Legal | Demonstrate channel authorization and identity/disclosure flow; review outreach authorization, communications law, dealer terms, and broker/agency implications. |
| P-005 | Keeps the buyer’s phone number private | evidence-required | None — architecture evidence required | — | Engineering + Privacy | Data-flow audit covering forms, email, telephony, vendors, logs, dealer messages, and exceptions. Avoid the absolute “private.” |
| P-006 | Handles the dealer inbox and email back-and-forth | legal-review-required | None — first-party build and legal review required | — | Product + Operations + Legal | Demonstrate sending, receiving, follow-up, identity disclosure, authorization, suppression, human escalation, and audit logs. |
| P-007 | Collects real written dealer quotes | legal-review-required | None — first-party build and legal review required | — | Product + Operations + Legal | Verify quote provenance and dealer authorization; define “quote,” currency, expiration, completeness, and nonbinding status. |
| P-008 | Compares written offers side by side | evidence-required | None — first-party build evidence required | — | Product + Engineering | Field-level accuracy tests, missing-data rules, normalization logic, and user-visible provenance. |
| P-009 | Compares or negotiates out-the-door pricing | legal-review-required | None — first-party build and legal review required | — | Product + Legal | Define included/excluded items and jurisdiction-specific taxes/fees; review negotiation, broker, agency, and price-representation implications. |
| P-010 | Removes or prevents junk fees/add-ons | remove | None — unsupported outcome and dealer control | — | Product + Legal | Do not promise control over a dealer’s offer. A future claim must describe a specific verified detection/display behavior. |
| P-011 | Runs or handles the deal | remove | None — undefined, unsupported scope | — | Product + Legal | “Deal” is overly broad and may imply representation, purchasing authority, or brokerage. |
| P-012 | Listens during a dealer call | legal-review-required | None — first-party build and legal review required | — | Engineering + Privacy + Legal | Technical demonstration plus consent, participant notice, interstate-call, vendor, security, and jurisdiction review. |
| P-013 | Records a dealer call | legal-review-required | None — first-party build and legal review required | — | Engineering + Privacy + Legal | Define whether recording occurs at all; complete consent, privacy, security, retention, deletion, access, and interstate-call review. |
| P-014 | Transcribes a dealer call live | legal-review-required | None — first-party build and legal review required | — | Engineering + Privacy + Legal | Accuracy/latency testing plus the complete audio and consent review required for P-012/P-013. |
| P-015 | Flags dealer tactics, hidden pivots, added fees, or financing changes | legal-review-required | None — first-party build and legal review required | — | Product + Legal | Define the taxonomy; measure precision/recall and harmful false positives; review advice, defamation, and consumer-finance implications. |
| P-016 | Tells the buyer what to say next in real time | legal-review-required | None — first-party build and legal review required | — | Product + Legal | Demonstrate latency and safety; review unauthorized-practice, agency, broker, consumer-finance, and disclosure concerns. |
| P-017 | Produces a post-call summary | legal-review-required | None — first-party build and legal review required | — | Engineering + Privacy + Legal | Test summary accuracy and document source audio/transcript handling, retention, deletion, and user correction. |
| P-018 | Produces a final deal-review checklist for fees, add-ons, and financing pivots | legal-review-required | None — first-party build and legal review required | — | Product + Legal | Define informational scope; test accuracy and omissions; review financial/legal advice implications. |
| P-019 | Creates a vehicle brief, deal-readiness checklist, or sample report | evidence-required | None — first-party build evidence required | — | Product | Specify output, test it, distinguish generic from personalized content, and disclose limitations. |
| P-020 | Contacts at least three dealers or any stated number of dealers | evidence-required | None — operating evidence required | — | Operations | Define eligibility, geography, dealer response, attempt vs. completed contact, and reporting period. |
| P-021 | Helps with leases | legal-review-required | None — scope and legal review required | — | Product + Legal | Adopt scope, validate calculations/disclosures, and review applicable licensing and financial-advice issues. |
| P-022 | Helps with trade-ins | legal-review-required | None — scope and legal review required | — | Product + Legal | Adopt scope and review valuation, referral, dealer, broker, and disclosure implications. |
| P-023 | Helps with out-of-state vehicles | legal-review-required | None — scope and legal review required | — | Product + Legal | Adopt geography and review interstate licensing, taxes, title/registration, communications, and recording issues. |
| P-024 | Provides a state-aware recording-consent checker | legal-review-required | None — legal content and build evidence required | — | Product + Legal | Counsel-owned jurisdictional method, effective-date tracking, change monitoring, escalation, and clear limitations. |
| P-025 | Provides human negotiators, concierges, brokers, agents, or manual review | business-decision-required | None — service model not adopted | — | Executive + Operations | Define roles, credentials, SLAs, disclosures, compensation, escalation, and legal/licensing review. |
| P-026 | Uses AI-only or fully automated handling | evidence-required | None — architecture evidence required | — | Product + Engineering | Document human involvement, exception handling, review paths, and accurate public disclosure. |
| P-027 | Organizes user-supplied vehicle preferences, budget, and search notes as a future concept | approved | Not applicable — narrow concept copy | — | Product | Use only the exact future-looking wording in the content contract. |
| P-028 | Presents dealer-provided pricing and terms as a future side-by-side concept | approved | Not applicable — narrow concept copy | — | Product | Use only as an unavailable concept; do not show fabricated data as a real offer. |
| P-029 | Prepares questions and talking points as a future concept | approved | Not applicable — narrow concept copy | — | Product | Use only as an unavailable concept and not as legal, financial, or individualized purchase advice. |

## D. Prices, commercial terms, and outcome claims

| ID | Proposed claim or term | Status | Source URL | Retrieved | Owner | Required methodology / condition |
|---|---|---|---|---|---|---|
| O-001 | Free plan with a vehicle brief, deal-readiness checklist, and sample report | business-decision-required | None — report recommendation only | — | Product + Finance | Adopt offer, define eligibility/limits, verify outputs, and review data/marketing terms. |
| O-002 | AI Negotiator: `$99 launch` | business-decision-required | None — report recommendation only | — | Executive + Finance | Cost model, offer scope, launch-period definition, taxes, billing trigger, support burden, and Legal review. |
| O-003 | AI Negotiator: `$149 standard` | business-decision-required | None — report recommendation only | — | Executive + Finance | Same as O-002; define whether “standard” is a real, regularly charged reference price. |
| O-004 | Live Deal Coach add-on: `$149 per purchase` | business-decision-required | None — report recommendation only | — | Executive + Finance | Define “purchase,” included sessions, service failure, billing, and required call-feature approvals. |
| O-005 | Complete Deal bundle: `$249 launch` | business-decision-required | None — report recommendation only | — | Executive + Finance | Adopt bundle components, launch period, support, fulfillment, taxes, and Legal review. |
| O-006 | Complete Deal bundle: `$349 standard` | business-decision-required | None — report recommendation only | — | Executive + Finance + Legal | Substantiate reference-price use, regular offering, launch discount, and price-anchoring compliance. |
| O-007 | One or two calls of up to 60 minutes each | business-decision-required | None — report recommendation only | — | Product + Operations + Finance | Define exact cap, scheduling, overages, unused calls, failures, refunds, and time-zone support. |
| O-008 | Price is per deal rather than subscription | business-decision-required | None — report recommendation only | — | Executive + Finance | Define a deal, duration, multiple vehicles/dealers, abandoned purchases, repeat use, taxes, and billing. |
| O-009 | Paying `$149–$349` is justified by preventing a modest pricing or fee mistake | remove | None — report inference, not product evidence | — | Product + Legal | Prohibited value/ROI anchor; requires verified product outcomes and fair comparison methodology. |
| O-010 | `1% savings is about $439` and `2% is about $879` against an average loan | remove | None — volatile market fact not re-sourced | — | Product + Legal | Do not publish. Future use requires a current primary dataset, correct denominator, representative comparison, calculation, date, and limitations. |
| O-011 | Saves money, “save thousands,” or any average/range/percentage savings | evidence-required | None — no customer outcome dataset | — | Data + Product + Legal | Pre-register sample, period, eligible deals, baseline/counterfactual, net/gross treatment, fees, financing, trade-ins, outliers, unsuccessful cases, and uncertainty; preserve auditable records. |
| O-012 | Prevents hidden fees or pricing mistakes | evidence-required | None — no outcome dataset | — | Product + Legal | Define the event and baseline, measure verified detection/prevention rather than exposure, include misses, and avoid guarantees. |
| O-013 | Raw AI cost is under `$1`, around `$1.57`, or otherwise low per transaction | remove | None — volatile vendor prices and modeled assumptions not re-sourced | — | Finance | Internal planning only; future publication requires current primary vendor URLs, exact workload, date, discounts, retries, other infrastructure, and reproducible calculation. |
| O-014 | Strong margins are available at `$99–$349` | remove | None — report inference only | — | Finance | Internal forecast, not website copy; requires a full unit-economics model. |
| O-015 | Prelaunch pricing has not been announced and no payment is accepted | approved | Not applicable — current contract | — | Product + Finance | Verify production behavior; any payment feature invalidates approval. |

## E. Proof, social proof, artifacts, and market facts

| ID | Proposed proof item or public fact | Status | Source URL | Retrieved | Owner | Required methodology / condition |
|---|---|---|---|---|---|---|
| E-001 | Press logos | remove | None — no coverage or permission supplied | — | Communications + Legal | Prohibited now. Future use requires exact coverage, trademark-use basis/permission, date, and no implication of endorsement. |
| E-002 | Partner logos | remove | None — no partnership supplied | — | Partnerships + Legal | Prohibited now. Future use requires an executed relationship and written brand approval. |
| E-003 | Dealer logos or participating-dealer claims | remove | None — no dealer participation supplied | — | Operations + Legal | Prohibited now. Future use requires a documented relationship and approved wording that does not overstate participation. |
| E-004 | Review count, star rating, or customer review | remove | None — no review source supplied | — | Customer + Legal | Prohibited now. Future use requires authentic source records, permission/platform rules, representative selection, date, and material-connection disclosures. |
| E-005 | Testimonials | remove | None — no customers/testimonials supplied | — | Customer + Legal | Prohibited now. Future use requires real customers, substantiated typicality/context, permission, and incentive/material-connection disclosure. |
| E-006 | Customer, deal, dealer, email, quote, or call counts | evidence-required | None — no operating dataset | — | Data + Product | Define the unit, deduplication, period, status, exclusions, audit query, snapshot date, and owner. |
| E-007 | Average savings or documented savings range | evidence-required | None — no outcome dataset | — | Data + Product + Legal | Use the full O-011 methodology; include unsuccessful/zero/negative outcomes and product fee. |
| E-008 | “No dealer affiliations” | remove | None — no corporate relationship record | — | Executive + Legal | Prohibited by instruction; avoid absolute independence claims. |
| E-009 | “No dealer compensation,” “no dealer kickbacks,” or equivalent | remove | None — no revenue/compensation record | — | Executive + Finance + Legal | Prohibited by instruction. Any future compensation disclosure requires a complete business-model review and new copy. |
| E-010 | Real dealer thread | evidence-required | None — no artifact supplied | — | Product + Privacy + Legal | Provenance, participant authorization, permissions, redaction, product/version date, no misleading edits, and context. |
| E-011 | Real negotiation transcript or recording | legal-review-required | None — no artifact supplied | — | Product + Privacy + Legal | Provenance plus recording consent, interstate-call, privacy, publicity, dealer/customer permission, editing/context, and retention review. |
| E-012 | Real written quote or fee breakdown | evidence-required | None — no artifact supplied | — | Product + Privacy + Legal | Verify dealer source/date/status, permission, redaction, completeness, expiration, taxes/fees, and nonbinding context. |
| E-013 | Product screenshot or dashboard as proof | evidence-required | None — no working build supplied | — | Product + Engineering | Capture from the release candidate with seeded/authorized data, version/date, and visible limitations. A design mockup is illustrative, not proof. |
| E-014 | Sample negotiation, inbox, quote, vehicle brief, transcript, or coaching card | approved | Not applicable — illustrative content only | — | Product + Brand | Must be fictional, must use the exact illustrative label, and must not contain savings, real identities, logos, or real-deal implications. |
| E-015 | FTC warned 97 dealership groups in March 2026 | remove | None — volatile public fact not re-sourced | — | Content | Not part of the approved preview. Future use requires the current direct FTC release URL, retrieval date, accurate scope, and confirmation that the number/date remain correctly contextualized. |
| E-016 | FTC advises focus on total cost and removing unwanted add-ons | remove | None — public guidance not re-sourced | — | Content + Legal | Not needed for preview. Future use requires the direct current FTC consumer-guidance URL, retrieval date, exact context, and non-endorsement framing. |
| E-017 | Experian Q1 2026 average new-loan amount `$43,925` and payment `$770` | remove | None — volatile dataset not re-sourced | — | Content + Data | Not needed for preview. Future use requires the direct primary report, retrieval date, population/period definitions, and no implication of product savings. |
| E-018 | Competitor prices: `$79`, `$999`, `$1,000`, or `$599–$799` | remove | None — volatile competitor facts not re-sourced | — | Product Marketing + Legal | Do not publish. Future comparison needs dated primary offer pages, equivalent-feature analysis, taxes/terms, monitoring, and comparative-advertising review. |
| E-019 | Users leave within 10–20 seconds or value must be clear within 10 seconds | remove | None — report citation not publishable | — | Design | Design rationale only, not website copy. |
| E-020 | SaaS median landing-page conversion is `3.8%` versus `6.6%` overall | remove | None — volatile benchmark not re-sourced | — | Growth | Internal planning only. Future use requires direct current primary benchmark, cohort definitions, sample, date, and comparability. |
| E-021 | Target visitor-to-lead conversion is `5%+` | remove | None — report inference only | — | Growth | Internal goal only; not a customer-facing proof claim. |
| E-022 | Major advice publishers recommend contacting at least three dealers | remove | None — public guidance not re-sourced | — | Content | Not needed for preview. Future use requires current direct source, retrieval date, scope, and no implied endorsement. |
| E-023 | Model/transcription vendor prices and per-session calculations | remove | None — volatile prices not re-sourced | — | Finance | Internal planning only; future use requires direct current vendor pricing URLs, retrieval date, workload and calculation methodology. |

No external public fact is approved for the prelaunch website. Consequently, no current primary-source URL is required for the approved copy path. The `None` entries above are deliberate: they show that the report’s tokens were not silently converted into evidence.

## F. Legal, privacy, and policy statements

| ID | Proposed statement or issue | Status | Source URL | Retrieved | Owner | Required methodology / condition |
|---|---|---|---|---|---|---|
| L-001 | Federal law provides a one-party-consent baseline for call recording | legal-review-required | None — report token is not a publishable legal source | — | Legal | Qualified counsel must determine whether, how, and where any statement applies to the actual product; record direct authoritative sources and effective dates. |
| L-002 | States may impose stricter recording rules | legal-review-required | None — report token is not a publishable legal source | — | Legal | Counsel-owned 50-state/jurisdiction analysis, conflict-of-law/interstate-call method, monitoring, and product restrictions. |
| L-003 | `We help you disclose and get consent where required.` | legal-review-required | None — proposed promise only | — | Product + Legal | Validate the exact consent experience, parties, timing, evidence, revocation, failure handling, geography, and whether the product can make this promise. |
| L-004 | The call coach is legal in a user’s state | legal-review-required | None — no jurisdictional analysis | — | Legal | Do not make a legality determination on the website without counsel-owned rules for the actual architecture, parties, and locations. |
| L-005 | The user does or does not need to disclose recording | legal-review-required | None — no jurisdictional analysis | — | Legal | Do not answer substantively in public FAQ until qualified review covers all relevant jurisdictions and interstate calls. |
| L-006 | Audio is or is not stored | legal-review-required | None — future architecture/policy undecided | — | Engineering + Privacy + Legal | Data-flow map, vendor contracts, buffering/caching/logging analysis, retention/deletion schedule, backups, access, security, and verified product behavior. |
| L-007 | Coaching happens locally or in the cloud | evidence-required | None — architecture undecided | — | Engineering + Privacy | Architecture diagram, vendor/subprocessor inventory, data locations, network behavior, telemetry, and user-facing accuracy. |
| L-008 | Audio is deleted immediately, retained for a period, or never retained | legal-review-required | None — policy and architecture undecided | — | Engineering + Privacy + Legal | Define “audio,” transcripts/embeddings/logs/backups, retention trigger, deletion SLA, legal holds, user controls, and verified implementation. |
| L-009 | Audio or transcripts are secure/private/confidential | legal-review-required | None — no security evidence | — | Security + Privacy + Legal | Threat model, access controls, encryption, vendor review, incident process, audits, exceptions, and carefully qualified wording. |
| L-010 | Calls across state lines are supported | legal-review-required | None — geography and legal method undecided | — | Product + Legal | Analyze participant location determination, conflict of laws, consent, availability restrictions, and failure handling. |
| L-011 | Company may act as a buyer’s agent, advocate, negotiator, concierge, or auto broker | legal-review-required | None — service model/licensing undecided | — | Executive + Legal | Jurisdiction-by-jurisdiction auto-broker/dealer/agency licensing analysis, contracts, compensation, fiduciary/disclosure duties, and restricted geographies. |
| L-012 | Company is not a broker/agent or no agency relationship is created | legal-review-required | None — disclaimer cannot override conduct | — | Legal | Review actual conduct and agreements. A label or disclaimer does not resolve licensing or agency status. |
| L-013 | Company is authorized to contact dealers, send email, follow up, or negotiate | legal-review-required | None — authorization flow absent | — | Product + Operations + Legal | Define user authorization, identity, channel, content, suppression/opt-out, dealer terms, records, revocation, and escalation. |
| L-014 | A refund is available before work begins | legal-review-required | None — no adopted policy | — | Finance + Operations + Legal | See C-016; align marketing, checkout, contract, support, and statutory rights. |
| L-015 | “Launch” and “standard” prices may be shown together | legal-review-required | None — no pricing history | — | Finance + Legal | Review reference-price/price-anchoring rules and require evidence that the comparison is genuine and not misleading. |
| L-016 | Product is available in named states, nationwide, or in the United States | legal-review-required | None — geography undecided | — | Executive + Legal | Adopt availability, complete licensing/recording/privacy review, and enforce location restrictions. |
| L-017 | Waitlist data is used only for product updates | legal-review-required | None — privacy notice and systems not reviewed | — | Growth + Privacy + Legal | Data inventory, notice, consent, email provider, sharing, retention, deletion/rights process, security, and form-to-system verification. |
| L-018 | Dealer or third-party data may be collected, displayed, or shared | legal-review-required | None — sources/permissions undecided | — | Product + Privacy + Legal | Source rights, terms, privacy, confidentiality, accuracy/correction, retention, and user/dealer notices. |
| L-019 | AI output is advice, a recommendation, or a guaranteed compliant response | remove | None — unsupported and high risk | — | Product + Legal | Do not characterize output this way. Future informational-assistance wording still requires accuracy and professional-scope review. |
| L-020 | `The preview provides general product information only and is not a substitute for advice from a qualified professional.` | approved | Not applicable — narrow prelaunch scope | — | Product | Must not be used to justify otherwise unreviewed functionality or claims. |

## Approval record requirements

When a claim becomes eligible for approval, append an evidence note or link to a repository record containing:

1. the exact approved wording;
2. the claim owner and approving names/roles;
3. direct source URL(s), where an external fact is used;
4. retrieval date and effective/reporting period;
5. reproducible methodology and underlying record location;
6. product version/build and verification date for capability claims;
7. limitations, exclusions, and expiration/re-review date;
8. Legal/Privacy approval reference where required; and
9. the content surfaces allowed to use it.

No unresolved statement may inherit approval from a neighboring row, a parent heading, a design mockup, or a competitor example.
