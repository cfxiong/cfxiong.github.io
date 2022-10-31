---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
I have published 1 book chapter, more than 50 peer-reviewed journal articles, and more than 30 conference proceedings and presentations on the topics of travel demand modeling, travel behavior, agent-based models, transportation big-data, advanced econometrics, and transportation and health. The most cited studies can be found here on this page. A full list of publications is available upon request. 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
