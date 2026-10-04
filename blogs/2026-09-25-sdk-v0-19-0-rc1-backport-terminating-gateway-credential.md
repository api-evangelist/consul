---
title: "sdk/v0.19.0-rc1: Backport terminating gateway credential injection structs (#23939)"
url: "https://github.com/hashicorp/consul/releases/tag/sdk%2Fv0.19.0-rc1"
date: "2026-09-25"
author: "krutibaraiya"
feed_url: "https://github.com/hashicorp/consul/releases.atom"
---
structs: backport inference gateway types to CE Adds the inference-gateway service kind, config entry kind, and their API, structs, agent-config, and proto surface so consumers such as consul-k8s can build against them. The inference gateway is an enterprise feature: CE rejects the config entry in Validate and the service kind in NodeService.Validate. Mirrors the CAMP structs backport ( #23842 ).
