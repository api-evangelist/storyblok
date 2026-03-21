# Storyblok (storyblok)
Storyblok is a headless CMS platform that enables developers and content teams to build, manage, and deliver structured content across web, mobile, and other digital channels. It provides a suite of APIs including REST and GraphQL content delivery, a management API for editorial automation, and an image transformation service, all accessible through its developer platform at storyblok.com/docs/api.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Headless CMS, Content Management, Content Delivery, REST, GraphQL, Media

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### Storyblok Content Delivery API v2
The Storyblok Content Delivery API v2 is a REST API that enables developers to fetch published content from a Storyblok space for delivery to end users across web, mobile, and other channels. It provides access to stories, datasources, links, tags, and asset metadata through predictable endpoints with token-based authentication. The API supports filtering, pagination, full-text search, and relation resolution, allowing developers to retrieve precisely the content their application needs. It is optimized for performance and available across multiple regional endpoints to minimize latency for global deployments.

**Human URL:** [https://www.storyblok.com/docs/api/content-delivery/v2](https://www.storyblok.com/docs/api/content-delivery/v2)


#### Tags:

 - Content Delivery, Headless CMS, REST, Content Management

#### Properties

- [Documentation](https://www.storyblok.com/docs/api/content-delivery/v2)
- [OpenAPI](openapi/storyblok-content-delivery-api-v2-openapi.yml)

### Storyblok Content Delivery API v1
The Storyblok Content Delivery API v1 is the original REST API for retrieving published content from Storyblok spaces. It provides access to stories, components, datasources, and links using a public or preview API token for authentication. While v2 is the recommended version for new projects, v1 remains supported for existing integrations and projects that have not yet migrated. The API follows standard REST conventions and returns JSON-encoded responses.

**Human URL:** [https://www.storyblok.com/docs/api/content-delivery/v1](https://www.storyblok.com/docs/api/content-delivery/v1)


#### Tags:

 - Content Delivery, Headless CMS, REST, Legacy

#### Properties

- [Documentation](https://www.storyblok.com/docs/api/content-delivery/v1)

### Storyblok Management API
The Storyblok Management API is a REST API that allows developers to programmatically create, read, update, and delete content and configuration within a Storyblok space. It supports managing stories, components, assets, datasources, collaborators, webhooks, and space settings. The API uses OAuth or personal access tokens for authentication and is suitable for building editorial tooling, content migration scripts, CI/CD pipelines, and automated publishing workflows. All write operations are scoped to individual spaces and respect role-based access control.

**Human URL:** [https://www.storyblok.com/docs/api/management](https://www.storyblok.com/docs/api/management)


#### Tags:

 - Content Management, Headless CMS, REST, Administration

#### Properties

- [Documentation](https://www.storyblok.com/docs/api/management)
- [OpenAPI](openapi/storyblok-management-api-openapi.yml)
- [AsyncAPI](asyncapi/storyblok-webhooks-asyncapi.yml)

### Storyblok GraphQL API
The Storyblok GraphQL API provides an alternative to the REST Content Delivery API, enabling developers to query published content using GraphQL syntax. It allows clients to request exactly the fields they need, reducing over-fetching and enabling efficient batched queries in a single request. The schema is automatically generated based on the component definitions configured in a Storyblok space. Regional endpoints are available for different geographic regions to reduce latency in global applications.

**Human URL:** [https://www.storyblok.com/docs/api](https://www.storyblok.com/docs/api)


#### Tags:

 - GraphQL, Content Delivery, Headless CMS, Query Language

#### Properties

- [Documentation](https://www.storyblok.com/docs/api)

### Storyblok Image Service
The Storyblok Image Service is a URL-based image transformation API that allows developers to resize, crop, convert, and optimize images hosted in Storyblok's asset CDN. Transformations are applied by constructing a specific URL with parameters that specify dimensions, format conversion, quality, focal point, and filter effects. The service eliminates the need for a separate image processing pipeline and is suitable for responsive images, thumbnails, and format-optimized delivery across web and mobile applications. Images are served via a global CDN for fast delivery.

**Human URL:** [https://www.storyblok.com/docs/concepts/assets](https://www.storyblok.com/docs/concepts/assets)


#### Tags:

 - Images, Media, Transformation, CDN

#### Properties

- [Documentation](https://www.storyblok.com/docs/concepts/assets)
- [OpenAPI](openapi/storyblok-image-service-openapi.yml)

## Common Properties

- [Portal](https://www.storyblok.com/developers)
- [Documentation](https://www.storyblok.com/docs)
- [Website](https://www.storyblok.com/)
- [PrivacyPolicy](https://www.storyblok.com/privacy-policy)
- [TermsOfService](https://www.storyblok.com/terms-of-service)
- [Support](https://www.storyblok.com/support)
- [Blog](https://www.storyblok.com/blog)
- [Login](https://app.storyblok.com/#!/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
