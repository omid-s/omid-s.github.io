---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---




* TOC
{:toc}

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Patents

{% for post in site.patents reversed %}
  {% include archive-single.html %}
{% endfor %}

## Posters

{% for post in site.posters reversed %}
  {% include archive-single.html %}
{% endfor %}
