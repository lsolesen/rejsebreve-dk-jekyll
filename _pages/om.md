---
permalink: /om/
excerpt: Rejsebreve er skrevet for at formidle voers rejse til Zambia i Afrika.
last_modified_at: 2023-01-25T04:47:02+01:00
layout: single
breadcrumbs: true
sitemap: false
author_profile: true
title: Om Rejsebreve formål og tilblivelse
---

Rejsebreve er vores families beretning om vores rejse til Zambia som frivillige på Eventure Plot.

## Tal om Rejsebreve

- Blogindlæg: {{ site.posts.size }}

## Forfattere

{% assign featured_authors = site.data.authors %}
{% for authors in featured_authors %}
  {% assign author=authors[1] %}
  {% include author.html author=author %}
{% endfor %}
