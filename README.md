# Packback (packback)

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
