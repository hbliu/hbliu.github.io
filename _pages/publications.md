---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<iframe border: none;
  src="https://bibbase.org/show?bib=https://bibbase.org/f/CXBcDH3rf8Ee4QN8p/Papers.bib"
  style="width:100%; height:100%;"
></iframe>
