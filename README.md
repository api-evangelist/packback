# Packback (packback)

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

Packback is an AI-powered instructional platform for higher education and K-12 that delivers real-time, formative feedback on student discussion and writing. Its products - Questions/Discussions, Writing and Deep Dives, and Originality - embed into a school's LMS through the IMS Global LTI standard rather than a public REST API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/packback/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/packback/refs/heads/main/apis.yml)

> **API availability note:** Packback does **not** publish a public, developer-facing REST API. Access to its products is delivered to students and instructors inside their Learning Management System (LMS) via the IMS Global **LTI** standard (1EdTech certified for LTI 1.0, 1.2, and 1.3 / LTI Advantage), providing single sign-on, deep linking, and gradebook/grade passback sync. The only published developer artifact is Packback's open-source [LTI 1.3 PHP tool-provider library](https://github.com/packbackbooks/lti-1-3-php-library). The OpenAPI document in this repo therefore uses an empty `paths` object and records this honestly.

## Tags

- Education
- EdTech
- AI
- Discussion
- Writing Feedback
- LTI
- LMS

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Packback Questions / Discussions

Inquiry-based student discussion product with built-in AI coaching that helps students ask better questions and write stronger responses, plus automated moderation for instructors. Accessed by students and instructors inside the LMS via LTI; no public REST API is published.

- **Human URL:** [https://packback.co/product/lti/](https://packback.co/product/lti/)

#### Tags

- Discussion
- Inquiry
- AI Coaching
- Education

#### Properties

- [Documentation](https://packback.co/platform/)
- [OpenAPI](openapi/packback-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/packback.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/packback.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Packback Writing / Deep Dives

Long-form writing and essay product (Writing, Deep Dives, Writing Lab) that gives students instant AI feedback on flow, structure, grammar, research quality, and formatting, with rubric-aligned AI-assisted grading for instructors. Delivered through the LMS via LTI; no public REST API is published.

- **Human URL:** [https://packback.co/product/deep-dives/](https://packback.co/product/deep-dives/)

#### Tags

- Writing Feedback
- Essays
- AI Coaching
- Grading

#### Properties

- [Documentation](https://packback.co/platform/)
- [OpenAPI](openapi/packback-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/packback.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/packback.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Packback LTI Integration

Packback's integration surface is the IMS Global LTI standard (1EdTech certified for LTI 1.0, 1.2, and 1.3 / LTI Advantage), providing single sign-on, deep linking, and gradebook/grade passback sync across Canvas, Blackboard, Brightspace, Moodle, Schoology, Google Classroom, ClassLink, Clever, and other IMS-compliant LMSs. Packback also maintains an open-source LTI 1.3 PHP tool-provider library.

- **Human URL:** [https://packback.co/lti-integration/](https://packback.co/lti-integration/)

#### Tags

- LTI
- LMS
- Single Sign-On
- Gradebook Sync
- Interoperability

#### Properties

- [Documentation](https://packback.co/lti-integration/)
- [GitHub](https://github.com/packbackbooks/lti-1-3-php-library)
- [OpenAPI](openapi/packback-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/packback.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/packback.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/packbackbooks)
- [LinkedIn](https://www.linkedin.com/company/packback)
- [Website](https://packback.co)
- [Documentation](https://help.packback.co)
- [Plans](plans/packback-plans-pricing.yml)
- [Rate Limits](rate-limits/packback-rate-limits.yml)
- [Fin Ops](finops/packback-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
