---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ul>

<li><b>Arroyo-Esquivel J</b>, Sanchez F, Barboza L. Infection model for analyzing biological control of coffee rust using bacterial anti-fungal compounds. <i>Mathematical BioSciences</i>, 307, 13-24. 
(<a href="https://doi.org/10.1016/j.mbs.2018.10.009">doi</a>) (<a href="https://arxiv.org/abs/1712.08958">arXiv</a>)</li>
</ul>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
