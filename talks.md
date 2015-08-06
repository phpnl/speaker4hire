---
layout: page
title: Talks
permalink: /talks/
---

Here be talks

<ul class="post-list">

{% assign sortedtalks = site.categories.talks | sort | reverse %}

  {% for talk in sortedtalks %}

    <li>
        <a class="post-link" href="{{ talk.url | prepend: site.baseurl }}">{{ talk.title }} - {{talk.speaker_name}}</a>
    </li>
  {% endfor %}
</ul>
