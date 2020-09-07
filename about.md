---
layout: page
title: Cosmological Horizon
description: About Me, CV, Projects etc.
sitemap:
    priority: 0.7
    lastmod: 2020-08-02
    changefreq: weekly
---

{% for item in site.aboutme %}
  <section class="post" id="{{item.identifier}}">
    <div class="box" >
      <h2>{{item.title}} </h2>
      {{item.content | markdownify }}
      </div>
  </section>
{% endfor %}
