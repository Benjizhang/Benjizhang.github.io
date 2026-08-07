---
layout: archive
title: "Books"
permalink: /books/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my books on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.books reversed %}
  {% include archive-single.html %}
{% endfor %}
