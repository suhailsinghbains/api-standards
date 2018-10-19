---
title: "Webhooks"
date: 2018-07-31T01:15:27+01:00
severity: should
category: callbacks
example_apis: []
---

### GET webhooks

Objects *retrieved* via webhooks by the API are in `camelCase`.

#### Examples

Nexmo Call Control Objects ([NCCO](https://developer.nexmo.com/voice/voice-api/ncco-reference)) examples:

* `eventUrl`
* `musicOnHold`
* `beepOnStart`

### POST webhooks

Objects *sent* via webhooks by the API are in `snake_case`.

#### Examples

[Voice API callbacks](https://developer.nexmo.com/voice/voice-api/webhook-reference)

* `conversation_uuid`
* `start_time`

### Why did we choose this?

Pre-existing standard

### Related Links

N/A
