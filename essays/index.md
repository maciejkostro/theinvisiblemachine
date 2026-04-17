---
title: "Essays"
description: "Essay index for the public static corpus."
section: site
sitemap: true
machine_readable: true
order: 5
last_modified: 2026-04-17
---

# Essays

The current essay sequence published in the project.

{% assign essays = site.pages | where: "section", "essay" | sort: "order" %}
{% for page in essays %}
## [{{ page.title }}]({{ site.baseurl }}{{ page.url }})

{{ page.description }}

- Published: {{ page.date_published }}
{% endfor %}
