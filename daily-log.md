---
layout: page
title: Daily Log
permalink: /daily-log/
---

{% for post in site.categories.log %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    {{ post.content }}
  </article>
{% endfor %}