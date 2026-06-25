# Quix (quix)

Quix is a Python-native stream-processing platform for real-time data and ML. It pairs Quix Streams - an open source (Apache 2.0) Python library for building containerized stream-processing applications on Apache Kafka - with Quix Cloud, a fully managed platform offering managed Kafka, Kubernetes deployments, and a set of HTTP and SignalR/WebSocket APIs for writing data in, reading data out in real time, and managing workspaces, topics, and deployments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/quix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/quix/refs/heads/main/apis.yml)

## Tags

- Stream Processing
- Real Time
- Kafka
- Python
- Streaming Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Quix Streaming Writer API

Write time-series parameter data, events, and definitions into Quix topics over HTTP REST (or SignalR), an alternative to the Quix Streams SDK for any HTTP-capable language. Authenticated with a Personal Access Token (PAT) bearer token.

- **Human URL:** [https://quix.io/docs/quix-cloud/apis/streaming-writer-api/overview.html](https://quix.io/docs/quix-cloud/apis/streaming-writer-api/overview.html)
- **Base URL:** `https://writer-{environmentId}.cloud.quix.io`

#### Tags

- Streaming
- Writer
- Ingest
- HTTP

#### Properties

- [Documentation](https://quix.io/docs/quix-cloud/apis/streaming-writer-api/overview.html)
- [OpenAPI](openapi/quix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Quix Streaming Reader API (Real-time)

Subscribe to live parameter data, events, definitions, active streams, topic metrics, and raw packages from Quix topics in real time over a Microsoft SignalR hub (WebSockets, with Long Polling fallback). Authenticated with a PAT via accessTokenFactory.

- **Human URL:** [https://quix.io/docs/quix-cloud/apis/streaming-reader-api/overview.html](https://quix.io/docs/quix-cloud/apis/streaming-reader-api/overview.html)
- **Base URL:** `https://reader-{environmentId}.cloud.quix.io/hub`

#### Tags

- Streaming
- Reader
- Real Time
- SignalR
- WebSocket

#### Properties

- [Documentation](https://quix.io/docs/quix-cloud/apis/streaming-reader-api/overview.html)
- [AsyncAPI](asyncapi/quix-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/quix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Quix Portal API (Management)

Account-wide HTTP REST API to automate and monitor Quix Cloud infrastructure - workspaces, topics, deployments, and persistent data - as an alternative to the Quix portal UI and CLI. Authenticated with a PAT bearer token.

- **Human URL:** [https://quix.io/docs/develop/apis-overview.html](https://quix.io/docs/develop/apis-overview.html)
- **Base URL:** `https://portal-api.platform.quix.io`

#### Tags

- Management
- Portal
- Automation

#### Properties

- [Documentation](https://quix.io/docs/develop/apis-overview.html)
- [OpenAPI](openapi/quix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Quix Topics & Deployments API

The topic- and deployment-management surface of the Portal API - create, list, update, and delete Kafka topics and manage the lifecycle (start, stop, status) of pipeline service deployments in a workspace.

- **Human URL:** [https://quix.io/docs/develop/apis-overview.html](https://quix.io/docs/develop/apis-overview.html)
- **Base URL:** `https://portal-api.platform.quix.io`

#### Tags

- Topics
- Deployments
- Infrastructure

#### Properties

- [Documentation](https://quix.io/docs/develop/apis-overview.html)
- [OpenAPI](openapi/quix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Quix Streams (Open Source)

Apache 2.0 open source Python library (pip install quixstreams) for building containerized stream-processing applications on Apache Kafka, using a declarative StreamingDataFrame and an Application runtime with windowing, stateful processing, streaming joins, and sources/sinks. Requires Python 3.9+; not a hosted API - included here as the OSS foundation of the platform.

- **Human URL:** [https://quix.io/docs/quix-streams/introduction.html](https://quix.io/docs/quix-streams/introduction.html)
- **Base URL:** `https://github.com/quixio/quix-streams`

#### Tags

- Open Source
- Python
- Kafka
- Library

#### Properties

- [Documentation](https://quix.io/docs/quix-streams/introduction.html)
- [Source Code](https://github.com/quixio/quix-streams)

## Common Properties

- [GitHub Organization](https://github.com/quixio)
- [LinkedIn](https://www.linkedin.com/company/quix)
- [Website](https://quix.io/)
- [Documentation](https://quix.io/docs/)
- [Plans](plans/quix-plans-pricing.yml)
- [Rate Limits](rate-limits/quix-rate-limits.yml)
- [Fin Ops](finops/quix-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
