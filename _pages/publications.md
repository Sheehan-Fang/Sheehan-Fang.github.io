---
layout: archive
title: "学术成果"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign research = site.publications | where_exp: "item", "item.publication_status != nil" | sort: "title" | sort: "conference_year" | reverse %}
{% for post in research %}
  {% include archive-single.html %}
{% endfor %}

{% for post in site.publications reversed %}
  {% unless post.publication_status %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}
