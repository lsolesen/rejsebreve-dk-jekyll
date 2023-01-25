---
layout: single
title: "Om Rejsebreve formål og tilblivelse"
permalink: /om/
excerpt: "Rejsebreve er skrevet for at formidle voers rejse til Zambia i Afrika."
author_profile: true
sitemap: false
breadcrumbs: true
---

Rejsebreve er vores families beretning om vores rejse til Zambia som frivillige på Eventure Plot.

## Forfattere

{% assign featured_authors = site.data.authors %}
{% for authors in featured_authors %}
  {% assign author=authors[1] %}
  {% include author.html author=author %}
{% endfor %}

## Tal om Rejsebreve

- Blogindlæg: {{ site.posts.size }}
