---
title: "Meet the Committee"
permalink: /committee/
layout: single
---

Here is the 2024/2025 Biosphere committee. Click on any member to read their full bio.

<div class="grid__wrapper">
  {% assign committee_members = site.committee | sort: "order" %}
  {% for person in committee_members %}
    <div class="grid__item">
      <article class="archive__item">
        <div class="archive__item-teaser">
          {% if person.avatar %}
            <img src="{{ person.avatar | relative_url }}" alt="{{ person.title }} avatar">
          {% endif %}
        </div>
        <h3 class="archive__item-title">
          <a href="{{ person.url | relative_url }}">{{ person.title }}</a>
        </h3>
        <p class="archive__item-excerpt">{{ person.position }}</p>
      </article>
    </div>
  {% endfor %}
</div>
