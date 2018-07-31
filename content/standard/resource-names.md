---
title: "Resource Names"
date: 2018-07-31T01:16:47+01:00
severity: should
category: uri
example_apis: []
---

All new API's shall adhere to the principles of REST. In doing so the following shall apply:

- Separate things into logical Collections e.g. `members`
- Collections are the collective term for Resources e.g. `member`
- Resources are nouns not verbs
- Collections are plurals

### Examples

* `/members` - `members` is the collection name
* `/members/bob` - Bob is the resource, he's a `member`

### Why did we choose this?

Pre-existing standard, based on Roy Fielding's dissertation

### Related Links

* [Roy Fielding's Disseration](http://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)
