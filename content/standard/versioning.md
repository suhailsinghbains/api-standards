---
title: "API Versioning"
date: 2018-07-31T01:17:16+01:00
severity: must
category: versioning
example_apis: []
---

All Nexmo APIs must support versioning.

### Structure

The version is given in the URI. The format for versioning is HOST/VERSION/API.

The only time we update an API's version is when a backwards compatibility break is made. Due to this, Nexmo APIs only support `major` API versions e.g. `/v1`, `/v2`

Beta programs may use either a `/beta` version or use `/v0.1`, `/v0.2` etc if breaking changes need to be communicated to consumers. For `/v0.x` releases breaking changes can be made between minor versions. Once the product is released, it must be updated to be `/v1` and our standard backwards compatibility rules are enforced.

### Examples

* https://api.nexmo.com/v0.2/dispatch
* https://api.nexmo.com/v1/calls
* https://api.nexmo.com/v3/media

### Why did we choose this?

#### Beta

Discussed in #api-standards due to the messaging/workflows release.

Participants:

* Aristoula Goulia
* Aurelien Favre
* Jamie Chapman
* Michael Heap

#### Non-beta

Pre-existing standard

### Related Links

N/A
