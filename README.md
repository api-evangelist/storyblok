# Storyblok (storyblok)

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
