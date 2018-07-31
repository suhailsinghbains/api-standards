---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
severity: must/should/may
category: json
example_apis:
  - redact
---

This is a short description of the standard

### Examples

This is a concrete example of how it should look

```json
{
  "demo": {
    "place": "an example here",
  }
}
```

### Why did we choose this?

What options did we evaluate? Why did we choose this solution over any others?

### Related Links

* [Example Link](https://tools.ietf.org/html/rfc0)

OR

N/A
