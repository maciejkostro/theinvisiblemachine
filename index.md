---
title: "The Invisible Machine"
description: "Public static corpus for essays and shared reference pages on digital finance in Europe."
sitemap: true
machine_readable: true
order: 1
---

# The Invisible Machine

This is a **static public corpus** for essays on digital finance in Europe and for shared reference pages.

## What is here

- an essay library
- shared reference pages
- machine-readable discovery files for search engines and AI systems

## Essays

{% assign essays = site.pages | where: "section", "essay" | sort: "order" %}
{% for page in essays %}
- [{{ page.title }}]({{ site.baseurl }}{{ page.url }}) — {{ page.description }}
{% endfor %}

## Reference pages

{% assign refs = site.pages | where: "section", "reference" | sort: "order" %}
{% for page in refs %}
- [{{ page.title }}]({{ site.baseurl }}{{ page.url }}) — {{ page.description }}
{% endfor %}

## Machine-readable endpoints

- [robots.txt]({{ site.baseurl }}/robots.txt)
- [sitemap.xml]({{ site.baseurl }}/sitemap.xml)
- [llms.txt]({{ site.baseurl }}/llms.txt)
- [corpus.json]({{ site.baseurl }}/corpus.json)
