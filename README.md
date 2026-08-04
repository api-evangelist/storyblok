# Storyblok (storyblok)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Storyblok is a headless content management system (CMS) with a visual editor that enables developers and content editors to collaboratively build and manage digital experiences. It provides APIs for content delivery, content management, image optimization, and webhook-based event notifications. Storyblok supports composable content through reusable components, multi-language content, and multi-site management with real-time collaboration features.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CMS
- Content Delivery
- Content Management
- Headless CMS
- Image Optimization
- REST API
- Visual Editor
- Webhooks

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Storyblok Content Delivery API

The Storyblok Content Delivery API v2 enables developers to fetch published content from a Storyblok space for delivery to web, mobile, and other channels. Provides access to stories, datasources, links, tags, and asset metadata with filtering, pagination, and relation resolution. Available across multiple regional endpoints for global low-latency delivery.

- **Human URL:** [https://www.storyblok.com/docs/api/content-delivery/v2](https://www.storyblok.com/docs/api/content-delivery/v2)
- **Base URL:** `https://api.storyblok.com/v2/cdn`

#### Tags

- Content Delivery
- Headless CMS
- REST API
- Stories

#### Properties

- [Documentation](https://www.storyblok.com/docs/api/content-delivery/v2)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-content-delivery-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/storyblok-content-delivery-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-content-delivery-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-image-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-image-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Storyblok Management API

The Storyblok Management API is a REST API for programmatically creating, reading, updating, and deleting content and configuration within a Storyblok space. Supports managing stories, components, assets, datasources, collaborators, webhooks, and space settings. Used for editorial tooling, content migration, CI/CD pipelines, and automated publishing workflows.

- **Human URL:** [https://www.storyblok.com/docs/api/management](https://www.storyblok.com/docs/api/management)
- **Base URL:** `https://mapi.storyblok.com/v1`

#### Tags

- Assets
- CMS
- Components
- Content Management
- REST API
- Stories
- Webhooks

#### Properties

- [Documentation](https://www.storyblok.com/docs/api/management)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/storyblok-content-delivery-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-content-delivery-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-image-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-image-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Storyblok Image Service

The Storyblok Image Service provides on-the-fly image resizing, cropping, filtering, and format conversion for assets stored in Storyblok. Supports fit-in resizing, smart cropping, focus-point-based cropping, and custom filter chains for quality adjustment, grayscale, and blur effects.

- **Human URL:** [https://www.storyblok.com/docs/image-service](https://www.storyblok.com/docs/image-service)
- **Base URL:** `https://a.storyblok.com`

#### Tags

- Image Optimization
- Image Processing
- Media

#### Properties

- [Documentation](https://www.storyblok.com/docs/image-service)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-image-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/storyblok-content-delivery-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-content-delivery-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-image-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-image-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Storyblok Webhooks

Storyblok emits webhook events when content actions occur in a space such as story publication, unpublication, deletion, asset upload, and pipeline stage transitions. AsyncAPI specification for webhook event schemas.

- **Human URL:** [https://www.storyblok.com/docs/guide/in-depth/webhooks](https://www.storyblok.com/docs/guide/in-depth/webhooks)

#### Tags

- AsyncAPI
- Events
- Real-Time
- Webhooks

#### Properties

- [Documentation](https://www.storyblok.com/docs/guide/in-depth/webhooks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/asyncapi/storyblok-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/storyblok-content-delivery-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-content-delivery-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-image-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-image-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/storyblok-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/storyblok-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/storyblok)
- [Portal](https://www.storyblok.com/)
- [Documentation](https://www.storyblok.com/docs)
- [Pricing](https://www.storyblok.com/pricing)
- [Blog](https://www.storyblok.com/blog)
- [About](https://www.storyblok.com/about)
- [Changelog](https://www.storyblok.com/changelog)
- [Case Studies](https://www.storyblok.com/customer-stories)
- [Contact](https://www.storyblok.com/contact)
- [Status Page](https://status.storyblok.com/)
- [Support](https://www.storyblok.com/support)
- [Privacy Policy](https://www.storyblok.com/legal/privacy-policy)
- [Terms of Service](https://www.storyblok.com/legal/terms-of-service)
- [Sign Up](https://app.storyblok.com/#!/signup)
- [Login](https://app.storyblok.com/)
- [Git Hub Org](https://github.com/storyblok)
- [SDK](https://www.storyblok.com/technologies)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
