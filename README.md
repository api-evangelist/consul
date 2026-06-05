# HashiCorp Consul (consul)

HashiCorp Consul is a distributed, highly available service-networking control plane that automates network configuration, discovers services, enables secure service-to-service communication, and exposes a strongly consistent key/value store. The Consul HTTP API is a REST + JSON service exposed by every Consul agent and server at /v1, gated by the X-Consul-Token header (apiKey) and ACL policies, supporting blocking queries via X-Consul-Index for streaming-style change detection.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- ACL
- Configuration
- Health Checking
- Key/Value Store
- Multi-Datacenter
- Open Source
- Service Discovery
- Service Mesh

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Consul HTTP API

The main HTTP API for interacting with Consul agents and servers. Endpoints are grouped under /agent (local agent state and registration), /catalog (cluster-wide service and node catalog), /health (health-checked service queries), /kv (key/value store), /acl (token, policy, and role management), /connect (service mesh CA, intentions), /config (central configuration entries), /event (user events), /session (locks and leadership), and /operator (Raft, autopilot, license).

- **Human URL:** [https://developer.hashicorp.com/consul/api-docs](https://developer.hashicorp.com/consul/api-docs)
- **Base URL:** `http://localhost:8500/v1`

#### Tags

- ACL
- Catalog
- Connect
- Health
- Key/Value
- Service Discovery
- Service Mesh

#### Properties

- [Documentation](https://developer.hashicorp.com/consul/api-docs)
- [OpenAPI](openapi/consul-http-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/consul-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/consul-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.hashicorp.com/consul/api-docs/api-structure)
- [A C L  Documentation](https://developer.hashicorp.com/consul/docs/security/acl)
- [GitHub Repository](https://github.com/hashicorp/consul)

## Common Properties

- [Website](https://www.consul.io)
- [Documentation](https://developer.hashicorp.com/consul)
- [Getting Started](https://developer.hashicorp.com/consul/tutorials/get-started-vms)
- [Tutorials](https://developer.hashicorp.com/consul/tutorials)
- [GitHub Organization](https://github.com/hashicorp)
- [GitHub Repository](https://github.com/hashicorp/consul)
- [Changelog](https://github.com/hashicorp/consul/releases)
- [Blog](https://www.hashicorp.com/blog/products/consul)
- [Community](https://discuss.hashicorp.com/c/consul)
- [Twitter](https://twitter.com/HashiCorp)
- [Terms of Service](https://www.hashicorp.com/terms-of-service)
- [Privacy Policy](https://www.hashicorp.com/privacy)
- [JSON-LD](json-ld/consul-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/consul-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/consul-kv-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/consul-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
