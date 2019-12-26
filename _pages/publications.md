---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

* TOC
{:toc}

{% include base_path %}

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Patents

{% for post in site.patents reversed %}
  {% include archive-single.html %}
{% endfor %}
