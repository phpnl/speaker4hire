---
layout: page
title: Speakers
permalink: /speakers/
---

Here be speakers

<ul class="post-list">
  {% for talk in site.categories.speakers %}

    <li>
        <a class="post-link" href="{{ talk.url | prepend: site.baseurl }}">{{ talk.title }}</a>
    </li>
  {% endfor %}
</ul>

