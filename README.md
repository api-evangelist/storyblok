# Storyblok (storyblok)
Storyblok is a headless content management system (CMS) with a visual editor that enables developers and content editors to collaboratively build and manage digital experiences. It provides APIs for content delivery, content management, image optimization, and webhook-based event notifications. Storyblok supports composable content through reusable components, multi-language content, and multi-site management with real-time collaboration features.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-02

## APIs

### Storyblok Content Delivery API
The Content Delivery API v2 enables fetching published content from a Storyblok space for delivery to web, mobile, and other channels. Provides access to stories, datasources, links, tags, and asset metadata with filtering, pagination, and relation resolution across multiple regional endpoints.

**Human URL:** [https://www.storyblok.com/docs/api/content-delivery/v2](https://www.storyblok.com/docs/api/content-delivery/v2)
**Base URL:** https://api.storyblok.com/v2/cdn

#### Tags

- Content Delivery, Headless CMS, REST API, Stories

#### Properties

- [Documentation](https://www.storyblok.com/docs/api/content-delivery/v2)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-content-delivery-api-v2-openapi.yml)

### Storyblok Management API
REST API for programmatically creating, reading, updating, and deleting content and configuration within a Storyblok space. Supports stories, components, assets, datasources, collaborators, webhooks, and space settings. Used for editorial tooling, content migration, CI/CD pipelines, and automated publishing workflows.

**Human URL:** [https://www.storyblok.com/docs/api/management](https://www.storyblok.com/docs/api/management)
**Base URL:** https://mapi.storyblok.com/v1

#### Tags

- Assets, CMS, Components, Content Management, REST API, Stories, Webhooks

#### Properties

- [Documentation](https://www.storyblok.com/docs/api/management)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-management-api-openapi.yml)

### Storyblok Image Service
URL-based image transformation API for resizing, cropping, converting, and optimizing images hosted in Storyblok's asset CDN. Transformations are defined in the URL path with dimensions, format, quality, and filter chain parameters.

**Human URL:** [https://www.storyblok.com/docs/image-service](https://www.storyblok.com/docs/image-service)
**Base URL:** https://a.storyblok.com

#### Tags

- Image Optimization, Image Processing, Media

#### Properties

- [Documentation](https://www.storyblok.com/docs/image-service)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-image-service-openapi.yml)

### Storyblok Webhooks
Storyblok emits webhook events when content actions occur in a space such as story publication, unpublication, deletion, asset upload, and pipeline stage transitions.

**Human URL:** [https://www.storyblok.com/docs/guide/in-depth/webhooks](https://www.storyblok.com/docs/guide/in-depth/webhooks)

#### Tags

- AsyncAPI, Events, Real-Time, Webhooks

#### Properties

- [Documentation](https://www.storyblok.com/docs/guide/in-depth/webhooks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/asyncapi/storyblok-webhooks-asyncapi.yml)

## Artifacts

### OpenAPI Specs

| File | Description |
|---|---|
| [storyblok-content-delivery-api-v2-openapi.yml](openapi/storyblok-content-delivery-api-v2-openapi.yml) | Content Delivery API v2 OpenAPI specification |
| [storyblok-management-api-openapi.yml](openapi/storyblok-management-api-openapi.yml) | Management API OpenAPI specification |
| [storyblok-image-service-openapi.yml](openapi/storyblok-image-service-openapi.yml) | Image Service OpenAPI specification |

### AsyncAPI Specs

| File | Description |
|---|---|
| [storyblok-webhooks-asyncapi.yml](asyncapi/storyblok-webhooks-asyncapi.yml) | Webhook event schemas |

### Capabilities

| File | Description |
|---|---|
| [content-management.yaml](capabilities/content-management.yaml) | Unified content management and delivery workflow |
| [shared/content-delivery.yaml](capabilities/shared/content-delivery.yaml) | Content Delivery API shared capability |
| [shared/management.yaml](capabilities/shared/management.yaml) | Management API shared capability |

### Rules

| File | Description |
|---|---|
| [storyblok-rules.yml](rules/storyblok-rules.yml) | Spectral ruleset enforcing Storyblok API conventions |

### JSON Schemas

| File | Description |
|---|---|
| [storyblok-story-schema.json](json-schema/storyblok-story-schema.json) | Story entity JSON Schema |
| [storyblok-component-schema.json](json-schema/storyblok-component-schema.json) | Component definition JSON Schema |
| [storyblok-webhook-payload-schema.json](json-schema/storyblok-webhook-payload-schema.json) | Webhook payload JSON Schema |

### JSON Structure

| File | Description |
|---|---|
| [storyblok-story-structure.json](json-structure/storyblok-story-structure.json) | Story object field documentation |

### JSON-LD

| File | Description |
|---|---|
| [storyblok-context.jsonld](json-ld/storyblok-context.jsonld) | JSON-LD context mapping Storyblok vocabulary |

### Examples

| File | Description |
|---|---|
| [storyblok-list-stories-example.json](examples/storyblok-list-stories-example.json) | List stories request/response example |
| [storyblok-create-story-example.json](examples/storyblok-create-story-example.json) | Create story request/response example |
| [storyblok-get-image-transform-example.json](examples/storyblok-get-image-transform-example.json) | Image Service transformation examples |

### Vocabulary

| File | Description |
|---|---|
| [storyblok-vocabulary.yml](vocabulary/storyblok-vocabulary.yml) | Domain vocabulary for Storyblok CMS concepts |

## Common Properties

- [Portal](https://www.storyblok.com/)
- [Documentation](https://www.storyblok.com/docs)
- [Pricing](https://www.storyblok.com/pricing)
- [Blog](https://www.storyblok.com/blog)
- [About](https://www.storyblok.com/about)
- [Changelog](https://www.storyblok.com/changelog)
- [Contact](https://www.storyblok.com/contact)
- [Status](https://status.storyblok.com/)
- [Support](https://www.storyblok.com/support)
- [Privacy Policy](https://www.storyblok.com/legal/privacy-policy)
- [Terms of Service](https://www.storyblok.com/legal/terms-of-service)
- [Sign Up](https://app.storyblok.com/#!/signup)
- [Login](https://app.storyblok.com/)
- [GitHub Org](https://github.com/storyblok)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
