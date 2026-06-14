# Storyblok GraphQL API

The Storyblok GraphQL API is a read-only content delivery endpoint that exposes published and draft content from a Storyblok space. It provides a strongly typed, automatically documented interface that mirrors the REST Content Delivery API v2. For each content type (component) defined in a Storyblok space, the GraphQL engine automatically generates two root query fields using the Pascal-cased component name: a singular form (e.g., `PageItem`) that returns one entry by `id`, `uuid`, or `full_slug`, and a plural form (e.g., `PageItems`) that returns a paginated list with filtering and sorting options. Because the schema is dynamically generated from space content types, the exact query fields available depend on the components configured in each Storyblok space.

Authentication is required for all requests. Clients must supply an access token via the `Token` HTTP request header, along with a `Version` header set to either `draft` (to retrieve unpublished preview content) or `published` (to retrieve live content). The `Content-Type` header must be `application/json`. A built-in `RateLimit` object with a `maxcost` field allows clients to estimate query cost before execution; the limit is 100 points per second and the server returns HTTP 429 when exceeded. Pagination is controlled via `per_page` (default 25, max 100) and `page` arguments available on all plural query fields. The API also exposes fixed built-in query fields — `DatasourceEntries`, `TagsItem`, and `Links` — that do not depend on user-defined content types.

The GraphQL API is available across multiple regional endpoints for low-latency global delivery, with the EU endpoint serving as the primary region. An interactive GraphQL playground is available for each region, accessible by appending a `?token=YOUR_ACCESS_TOKEN` query parameter to the browser URL.

**Endpoint:** https://gapi.storyblok.com/v2/api

**Regional Endpoints:**
- EU: https://gapi.storyblok.com/v2/api
- US: https://gapi-us.storyblok.com/v2/api
- Canada: https://gapi-ca.storyblok.com/v2/api
- Australia: https://gapi-ap.storyblok.com/v2/api
- China: https://gapi.storyblokchina.cn/v2/api

**Documentation:** https://www.storyblok.com/docs/api/graphql

**References:**
- Documentation: https://www.storyblok.com/docs/api/graphql
- GettingStarted: https://storyblok.com/docs/api/graphql/getting-started/graphql-playground
