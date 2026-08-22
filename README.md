# Riiid (riiid)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Riiid (now operating as Socra AI) is an AI education technology company whose proprietary deep-knowledge-tracing and score-prediction models power adaptive learning. Its consumer product Santa (AI TOEIC / TOEFL test prep) and its R.Inside AI-as-a-Service offering bring real-time student modeling to partners. Riiid does not publish a public, self-serve developer API; its AI is delivered through B2B partner integrations and packaged products.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/riiid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/riiid/refs/heads/main/apis.yml)

> **Availability note:** Riiid has no documented public, self-serve API. The surfaces below describe Riiid's AI products and partner/B2B solutions honestly. The OpenAPI definition uses an empty `paths: {}` object because no public endpoints are documented.

## Tags

- AI
- Education
- Adaptive Learning
- Knowledge Tracing
- EdTech

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Riiid Adaptive Learning

Riiid's adaptive learning engine analyzes learner interaction data in real time to recommend personalized study paths and content. It is delivered inside Riiid/Socra products (Santa) and to partners via integration, not as a documented public self-serve API.

- **Human URL:** [https://corp.socra.ai/](https://corp.socra.ai/)

#### Tags

- Adaptive Learning
- Personalization
- Recommendation

#### Properties

- [Documentation](https://corp.socra.ai/)
- [OpenAPI](openapi/riiid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/riiid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/riiid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Riiid Knowledge Tracing

Proprietary deep knowledge tracing and score-prediction models (built on 100M+ student interactions, the EdNet dataset) estimate a learner's mastery and predict test outcomes in real time. Exposed through Riiid products and partner solutions; no public API endpoint is documented.

- **Human URL:** [https://corp.socra.ai/](https://corp.socra.ai/)

#### Tags

- Knowledge Tracing
- Score Prediction
- Deep Learning

#### Properties

- [Documentation](https://corp.socra.ai/)
- [Source Code](https://github.com/riiid/ednet)
- [OpenAPI](openapi/riiid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/riiid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/riiid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Riiid Santa

Santa is Riiid's consumer AI tutor app for standardized English tests (TOEIC, and TOEFL via an ETS content partnership). It is distributed as iOS / Android mobile applications with no documented public developer API.

- **Human URL:** [https://apps.apple.com/us/app/santa-ai-toeic/id1148006701](https://apps.apple.com/us/app/santa-ai-toeic/id1148006701)

#### Tags

- Santa
- Test Prep
- TOEIC
- TOEFL

#### Properties

- [Documentation](https://corp.socra.ai/)
- [Sign Up](https://apps.apple.com/us/app/santa-ai-toeic/id1148006701)
- [OpenAPI](openapi/riiid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/riiid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/riiid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Riiid Partner Solutions

B2B / AI-as-a-Service (R.Inside) engagements that embed Riiid's adaptive learning and knowledge-tracing AI into partner education platforms. Access is sales-led and contract-based via partnership@socra.ai; no public self-serve API is published.

- **Human URL:** [https://corp.socra.ai/](https://corp.socra.ai/)

#### Tags

- Partner Solutions
- AIaaS
- B2B
- R.Inside

#### Properties

- [Documentation](https://corp.socra.ai/)
- [OpenAPI](openapi/riiid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/riiid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/riiid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/riiid)
- [LinkedIn](https://www.linkedin.com/company/riiid)
- [Website](https://www.riiid.com)
- [Documentation](https://corp.socra.ai/)
- [Plans](plans/riiid-plans-pricing.yml)
- [Rate Limits](rate-limits/riiid-rate-limits.yml)
- [Fin Ops](finops/riiid-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
