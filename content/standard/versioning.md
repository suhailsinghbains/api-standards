---
title: "Versioning"
date: 2018-07-31T01:17:16+01:00
severity: must
category: uri
example_apis: []
---

All Nexmo APIs must support versioning.

When the decision has been taken to deprecate an API:

* There will be a 1 year grace period between the announcement and the moment when API is deactivated.
* Warning emails will be sent to the API at regular intervals before the deprecation time
* A guide will be supplied to customers explaining how to migrate to the replacement API with the initial deprecation notice.

### Structure

The version is given in the URI. The format for versioning is HOST/VERSION/API 

### Examples

* https://api.nexmo.com/v1/calls
* https://api.nexmo.com/v3/media

### Why did we choose this?

Pre-existing standard

### Related Links

N/A
