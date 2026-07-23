# Launch Blockers and Required Decisions

**Assessment date:** 2026-07-22  
**Assessed launch:** public prelaunch preview with a waitlist  
**Not assessed as launch-ready:** beta, human-assisted service, automated dealer outreach, negotiation, call coaching, or paid purchase

The source report supplies strategy, suggested copy, and suggested pricing. It does not supply operating evidence, adopted policies, customer proof, legal review, or a public brand. The narrow prelaunch path in `docs/content-contract.md` can launch only after the preview blockers below are closed.

## 1. Prelaunch preview blockers

| ID | Blocker | Owner | Exit evidence |
|---|---|---|---|
| PL-01 | Public brand is unresolved; `{BRAND_NAME}` cannot render. | Executive + Brand | Approved brand, basic clearance process completed, configured site-wide, and “Dealer AI” removed as the default public category. |
| PL-02 | Launch state and conversion must be enforced as prelaunch + waitlist only. | Product | Written sign-off that no beta, signup, vehicle brief delivery, purchase, consultation, outreach, or negotiation is offered from the preview. |
| PL-03 | Waitlist form fields, consent, and follow-up use are not defined. | Growth + Privacy + Legal | Final field list, plain-language notice, communication consent, email provider/data-flow record, retention/deletion approach, and approved confirmation copy. |
| PL-04 | The preview must not take payment. | Product + Engineering + Finance | Release check showing no checkout, payment link, card field, paid plan, invoice request, or payment-triggering integration. |
| PL-05 | The preview must not contact dealers or share registrant data with dealers. | Product + Engineering + Privacy | Integration/data-flow check showing no dealer recipient, outreach automation, CRM route, webhook, or third-party sharing outside the disclosed waitlist flow. |
| PL-06 | The preview must not accept, capture, upload, record, transcribe, or store call audio. | Engineering + Privacy | Release check covering UI, APIs, vendor configurations, logging, uploads, browser permissions, and storage. |
| PL-07 | Any product mockups or negotiation materials must be unambiguously illustrative. | Product + Brand | Artifact inventory; fictional names/data; exact label `Illustrative product concept — not a real dealer interaction.` displayed on each artifact. |
| PL-08 | Unapproved claims from the report may still be present in designs, metadata, or hidden content. | Content + Product | Full content QA across visible copy, alt text, title/description, Open Graph, structured data, image text, form states, footer, and dormant/hidden components against the claims register. |
| PL-09 | Privacy and contact surfaces for the waitlist preview are not supplied. | Privacy + Legal + Operations | Approved privacy notice, accurate contact route, controller/company identity, effective date, and any required terms linked from the form/footer. |
| PL-10 | Final owner approval is absent. | Product + Legal + Privacy + Brand | Dated sign-off on the exact release-candidate copy and behavior; no approval by silence. |

### Minimum preview release test

The release candidate passes only if all answers are “yes”:

- Does it display an approved brand instead of `{BRAND_NAME}` or “Dealer AI” as the public category?
- Does the hero match the exact approved prelaunch copy?
- Is `Join the waitlist` the sole primary conversion?
- Does every product concept state that features are not available in the preview?
- Are all concept artifacts visibly labeled illustrative?
- Are pricing, refunds, geography, availability, savings, customer proof, dealer proof, press/partner proof, and compensation claims absent except for the approved “not announced/no payment” language?
- Is there no live vehicle search, brief delivery, account signup, checkout, dealer contact, negotiation, call input, recording, transcription, or coaching flow?
- Does the waitlist notice accurately describe collection and follow-up?
- Do metadata, structured data, screenshots, and hidden states meet the same claim rules as visible body copy?
- Are Privacy/Legal links and an accurate contact route present?

## 2. Blockers before any beta or operational-capability claim

These do not block the narrow waitlist preview. They block calling the product a beta, inviting people to use it, or changing planned capabilities into present tense.

| ID | Blocker | Owner | Exit evidence |
|---|---|---|---|
| OP-01 | No reproducible evidence of inventory search or matching. | Product + Engineering | Defined sources and permissions; dated end-to-end tests for freshness, matching, deduplication, geography, failures, and limitations. |
| OP-02 | No verified vehicle brief, comparison, checklist, or deal-plan output. | Product + Engineering | Release-candidate outputs, accuracy rubric, test set, failure/omission analysis, limitations, and user correction process. |
| OP-03 | Dealer outreach authority and workflow are undefined. | Product + Operations + Legal | Approved user authorization; sender identity; communication channels; dealer terms; opt-out/suppression; audit trail; revocation; failure and escalation handling. |
| OP-04 | Dealer outreach may create auto-broker, agency, dealer, or other licensing obligations. | Executive + Legal | Qualified jurisdiction-by-jurisdiction review tied to actual conduct, compensation, contracts, and launch geography; required licenses/registrations obtained or product scope restricted. |
| OP-05 | Quote provenance and “out-the-door” methodology are undefined. | Product + Operations + Legal | Definition of a quote and OTD amount, source/date/expiration, included/excluded fees and taxes, missing-data rules, nonbinding disclosure, and verified comparison tests. |
| OP-06 | Human involvement is undecided. | Executive + Operations | Adopt AI-only, human-reviewed, or concierge model; document roles, credentials, SLAs, escalation, disclosures, compensation, and applicable legal review. |
| OP-07 | Product limitations and failure handling are undefined. | Product + Engineering + Support | Known-limitations record, fallback/escalation path, user correction, incident/support workflow, and accurate public disclosure. |
| OP-08 | Geography is undecided. | Executive + Product + Legal | Approved launch locations plus enforced restrictions reflecting licensing, privacy, communications, consumer-protection, and any call-feature review. |
| OP-09 | Third-party inventory, dealer, email, and user-data rights are unresolved. | Product + Privacy + Legal | Vendor/source contracts and terms review; permitted uses; accuracy/correction; confidentiality; retention; sharing; subprocessor disclosures. |
| OP-10 | Product and professional-scope boundaries are unresolved. | Product + Legal | Approved wording and behavior for informational assistance versus negotiation, brokerage, legal advice, financial advice, valuation, leasing, trade-ins, financing, and purchase decisions. |

## 3. Blockers before live call listening, recording, transcription, or coaching

No call feature may launch or be described as available until all items in this section are closed. This section flags issues for qualified review and does not provide legal advice.

| ID | Blocker | Owner | Exit evidence |
|---|---|---|---|
| CALL-01 | Recording and interception consent requirements are unresolved. | Legal | Counsel-owned analysis for actual technical architecture, all parties, participant locations, jurisdictions, and feature modes; approved consent/notice flow. |
| CALL-02 | Interstate call handling is unresolved. | Legal + Product | Method for determining relevant locations, conflict-of-law approach, restricted/blocked cases, consent fallback, and change monitoring. |
| CALL-03 | It is undecided whether audio is merely streamed, buffered, recorded, or retained. | Engineering + Privacy | Complete architecture/data-flow diagram including browser/device, network, subprocessors, temporary buffers, logs, caches, backups, transcripts, embeddings, and analytics. |
| CALL-04 | Audio and transcript privacy policy is absent. | Privacy + Legal | Purpose, lawful basis/authorization, notice, collection, access, disclosure, subprocessors, data location, retention, deletion, backups, user rights, legal holds, and contact process. |
| CALL-05 | Security controls for audio/transcripts are unverified. | Security + Engineering | Threat model, encryption, secrets/access controls, tenant isolation, vendor review, logging, incident response, deletion validation, and security approval. |
| CALL-06 | Consent evidence, withdrawal, and failure behavior are undefined. | Product + Legal | Approved screens/scripts, consent record, participant refusal/withdrawal handling, feature shutoff, audit trail, and user support process. |
| CALL-07 | Transcription quality and latency are unverified. | Product + Engineering | Representative test set, word/error methodology, speaker/noise/accent conditions, latency distribution, outage behavior, and limitations. |
| CALL-08 | Real-time suggestions could be inaccurate or cross legal, financial, broker, or agency boundaries. | Product + Legal | Defined output scope; safety policy; test set; harmful false-positive/negative analysis; prohibited advice; escalation; user-visible limitations. |
| CALL-09 | “Tactic,” fee, financing, and term detection is not defined or validated. | Product + Legal | Taxonomy, source basis, precision/recall, uncertainty display, correction path, defamation/fairness review, and no guarantee language. |
| CALL-10 | Use of real calls as marketing proof is unauthorized. | Product + Privacy + Legal | Separate participant permissions, recording/usage review, redaction, publicity/confidentiality review, context-preserving edit log, and retention approval. |

## 4. Blockers before pricing, checkout, refunds, or paid launch

| ID | Blocker | Owner | Exit evidence |
|---|---|---|---|
| PAY-01 | The offer and price are not adopted. | Executive + Product + Finance | Approved package(s), exact price, currency, taxes, billing trigger, service period, included work, usage caps, overages, exclusions, and support. |
| PAY-02 | “Deal,” “purchase,” “launch,” and “standard price” are undefined. | Product + Finance + Legal | Contract and marketing definitions aligned across pricing page, checkout, receipt, support, and terms. |
| PAY-03 | Suggested `$99`, `$149`, `$249`, and `$349` prices lack business approval. | Executive + Finance | Decision memo with unit economics, acquisition/support assumptions, capacity, taxes, vendor cost, and operational readiness. |
| PAY-04 | Launch/standard price anchoring has not been reviewed. | Finance + Legal | Evidence and qualified review showing any reference price, discount, duration, and availability are genuine and not misleading. |
| PAY-05 | Cancellation/refund policy is not adopted. | Operations + Finance + Legal | Exact trigger for work beginning, cancellation method, timing, partial work, failed service, refund method/SLA, exceptions, chargebacks, and statutory rights. |
| PAY-06 | Marketing refund copy and operational refund behavior are not aligned. | Product + Operations | End-to-end tests from checkout through cancellation, support, ledger, refund, email notice, and exception handling. |
| PAY-07 | “Flat fee,” “no hidden fees,” and “no surprise add-ons” are unsupported. | Finance + Legal | Complete fee schedule and approved narrower wording. Do not promise control over dealer fees/add-ons. |
| PAY-08 | Terms and service-fulfillment contract are absent. | Legal + Operations | Approved customer agreement covering scope, authorization, limitations, third parties, timing, cancellation/refunds, disputes, privacy, and required disclosures. |
| PAY-09 | Compensation, referral, affiliate, or dealer revenue model is undecided or undocumented. | Executive + Finance + Legal | Complete revenue-flow record and accurate disclosure. Do not use “no dealer kickbacks” or equivalent in the meantime. |
| PAY-10 | Licensing and geography may depend on paid conduct and compensation. | Executive + Legal | Qualified review for actual packages, conduct, compensation, human involvement, and jurisdictions; licenses/restrictions implemented. |

## 5. Blockers before publishing proof or performance claims

| ID | Blocker | Owner | Exit evidence |
|---|---|---|---|
| PROOF-01 | No customer, deal, dealer, email, quote, or call dataset was supplied. | Data + Product | Auditable source of truth with unit definitions, deduplication, date range, inclusion/exclusion rules, query, owner, and snapshot date. |
| PROOF-02 | No savings methodology or outcome records were supplied. | Data + Product + Legal | Predefined baseline/counterfactual, sample, period, product fee, taxes/fees, financing/trade-in treatment, zero/negative outcomes, outliers, uncertainty, and auditable records. |
| PROOF-03 | No testimonials, ratings, or reviews were supplied. | Customer + Legal | Authentic records, permissions, platform rules, incentive/material-connection disclosure, date, context, and representative-use review. |
| PROOF-04 | No press or partner relationship evidence was supplied. | Communications + Partnerships + Legal | Exact coverage or executed relationship plus trademark/brand-use permission and non-endorsement review. |
| PROOF-05 | No dealer participation or logo permission was supplied. | Operations + Legal | Executed relationship, exact scope, current status, approved wording, and logo/brand permission. |
| PROOF-06 | No real negotiation artifact was supplied. | Product + Privacy + Legal | Provenance, participant authorization, consent/recording review, permissions, redaction, context, product/version/date, and approved retention/use. |
| PROOF-07 | Current product UI was not supplied as evidence. | Product + Engineering | Screenshot/demo captured from the release candidate, using authorized or seeded data, with version/date and disclosed limitations. |
| PROOF-08 | Report citations are internal tokens, not publishable sources. | Content | Replace any public fact intended for the site with a direct current primary-source URL, retrieval date, owner, status, method, context, and re-review date in the claims register. |
| PROOF-09 | Volatile competitor, market, regulatory, and vendor-price facts were not re-sourced. | Content + Product Marketing | Keep them off the site, or complete the primary-source and methodology record before approval. |

## 6. Remaining business decisions

These decisions remain open after this content-truth pass.

| Decision | Default until decided | Required decision owner |
|---|---|---|
| Public brand name | Use internal `{BRAND_NAME}` token in documents only; block production rendering. | Executive + Brand |
| Launch phase | Prelaunch only; not beta, human-assisted, or operational. | Executive + Product |
| Primary conversion | Waitlist only. | Product + Growth |
| Waitlist fields | Email only is the minimum-risk default; any additional vehicle/location data requires purpose and privacy approval. | Growth + Privacy |
| Waitlist communications | Product-launch updates only; no dealer sharing or outreach. | Growth + Privacy |
| Product roadmap | Only the three exploratory outcomes in the content contract may appear. Dealer outreach and call features remain uncommitted publicly. | Product |
| Service model | No claim of AI-only, human-assisted, concierge, broker, or agent service. | Executive + Operations |
| Dealer outreach channel and authorization | No outreach in preview. | Product + Operations + Legal |
| Inventory and dealer-data sources | No current source or coverage claim. | Product + Partnerships + Legal |
| Definition of quote and OTD price | No quote/OTD claim. | Product + Operations + Legal |
| Support for leasing, trade-ins, financing, or out-of-state purchases | Not announced. | Product + Legal |
| Geographic availability | Not announced; waitlist does not guarantee availability. | Executive + Legal |
| Call-feature architecture | No audio accepted in preview; future stream/record/store/process decisions unresolved. | Product + Engineering + Privacy |
| Consent and interstate-call model | No call feature until qualified review is complete. | Legal |
| Pricing model | Not announced; no payment accepted. | Executive + Finance |
| Suggested price points | `$99/$149/$249/$349` remain unapproved report recommendations. | Executive + Finance |
| Usage caps | No adopted call, dealer, vehicle, time, or deal limits. | Product + Operations + Finance |
| Refund/cancellation policy | Not applicable while no payment is accepted; no future promise approved. | Finance + Operations + Legal |
| Compensation/referral/affiliate model | No independence or “no kickbacks” statement permitted. | Executive + Finance + Legal |
| Proof strategy | Illustrative process concept only; no savings, testimonials, counts, logos, or real-deal proof. | Product + Brand |
| Evidence owner and repository | No evidence system assigned. | Product + Data |
| Privacy notice and data retention | Must be decided for the waitlist before preview launch. | Privacy + Legal |

## 7. Qualified-review flags

The following require qualified review tied to the actual product and launch locations:

- recording consent and participant disclosure;
- audio capture, streaming, buffering, storage, retention, deletion, security, and subprocessors;
- interstate calls and location determination;
- privacy notices, consent, user rights, waitlist data, and dealer/customer data sharing;
- auto-broker, dealer, agency, buyer-representative, and related licensing;
- refund, cancellation, service-start, and consumer-contract terms;
- launch/standard/reference-price anchoring and discount presentation;
- authority to contact dealers, sender identity, email/telephony rules, suppression, and revocation;
- legal/financial advice boundaries, financing, leasing, trade-ins, valuations, and real-time suggestions;
- geographic availability and enforcement of restrictions;
- use of real negotiations, dealer communications, customer data, names, logos, and recordings in marketing.

These are issue flags, not legal conclusions or legal advice.

## 8. Launch recommendation

Do not launch a beta, paid service, dealer-outreach flow, negotiation service, or call feature on the strength of the report.

A narrow prelaunch preview is supportable after `PL-01` through `PL-10` are closed. Its safe path is:

- configurable approved brand;
- descriptor `buyer-side AI for car buying`;
- exact prelaunch hero and reassurance;
- three future-looking product-concept outcomes;
- clearly illustrative artifacts only;
- waitlist registration as the sole conversion;
- no payment, dealer contact, audio, personalized output, availability promise, or proof claim; and
- the approved FAQ, privacy notice, and contact route.
