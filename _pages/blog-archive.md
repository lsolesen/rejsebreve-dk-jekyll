---
layout: posts
permalink: /blog/
excerpt: "Rejsebreve blog er for os der gerne vil blive klogere på frisbeesporten, discgolf og ultimate."
title: Rejsebreves blog
seo_title: "Blog om rejse til Zambia og Eventure | Rejsebreve"
classes: wide
author_profile: true
gallery:
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=65735
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=65735
    alt: Backpackerlife.dk
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=45001
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=45001
    alt: Rejsegear
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=57101
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=57101
    alt: Flypenge
---

{% assign site_posts = site.posts | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
<h2>Seneste opdateringer på Rejsebreves blog</h2>
<div class="feature__wrapper">
  {% for post in site_posts limit:16 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
{% endif %}

{% include gallery %}