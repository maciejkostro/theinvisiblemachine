---
title: "References"
description: "Shared reference pages for the public static corpus."
section: site
sitemap: true
machine_readable: true
order: 6
last_modified: 2026-04-17
---

# Reference pages

These pages form the shared reference section of the corpus.

{% assign refs = site.pages | where: "section", "reference" | sort: "order" %}
{% for page in refs %}
## [{{ page.title }}]({{ site.baseurl }}{{ page.url }})

{{ page.description }}
{% endfor %}
