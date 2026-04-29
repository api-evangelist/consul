# HashiCorp Consul (consul)

HashiCorp Consul is a distributed, highly available service-networking control plane that automates network configuration, discovers services, enables secure service-to-service communication, and exposes a strongly consistent key/value store. The Consul HTTP API is a REST + JSON service exposed by every Consul agent and server at /v1, gated by the X-Consul-Token header (apiKey) and ACL policies, supporting blocking queries via X-Consul-Index for streaming-style change detection.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/consul/refs/heads/main/apis.yml)

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
- **Modified:** 2026-04-29

## APIs

### Consul HTTP API
The main HTTP API for interacting with Consul agents and servers. Endpoints are grouped under /agent (local agent state and registration), /catalog (cluster-wide service and node catalog), /health (health-checked service queries), /kv (key/value store), /acl (token, policy, and role management), /connect (service mesh CA, intentions), /config (central configuration entries), /event (user events), /session (locks and leadership), and /operator (Raft, autopilot, license).

**Human URL:** [https://developer.hashicorp.com/consul/api-docs](https://developer.hashicorp.com/consul/api-docs)

**Base URL:** `http://localhost:8500/v1`

#### Tags

- ACL, Catalog, Connect, Health, Key/Value, Service Discovery, Service Mesh

#### Properties

- [Documentation](https://developer.hashicorp.com/consul/api-docs)
- [OpenAPI](openapi/consul-http-api.yml)
- [Authentication](https://developer.hashicorp.com/consul/api-docs/api-structure)
- [ACL Documentation](https://developer.hashicorp.com/consul/docs/security/acl)
- [GitHub Repository](https://github.com/hashicorp/consul)

## Common Properties

- [Website](https://www.consul.io)
- [Documentation](https://developer.hashicorp.com/consul)
- [Getting Started](https://developer.hashicorp.com/consul/tutorials/get-started-vms)
- [Tutorials](https://developer.hashicorp.com/consul/tutorials)
- [GitHub Organization](https://github.com/hashicorp)
- [GitHub Repository](https://github.com/hashicorp/consul)
- [Change Log](https://github.com/hashicorp/consul/releases)
- [Blog](https://www.hashicorp.com/blog/products/consul)
- [Community](https://discuss.hashicorp.com/c/consul)
- [Twitter](https://twitter.com/HashiCorp)
- [Terms of Service](https://www.hashicorp.com/terms-of-service)
- [Privacy Policy](https://www.hashicorp.com/privacy)
- [JSON-LD Context](json-ld/consul-context.jsonld)
- [Service JSON Schema](json-schema/consul-service-schema.json)
- [KV JSON Schema](json-schema/consul-kv-schema.json)
- [Spectral Ruleset](rules/consul-rules.yml)
- [Naftiko Capabilities](capabilities/consul-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
