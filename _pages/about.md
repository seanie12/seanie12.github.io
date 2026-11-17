---
permalink: /
layout: research
redirect_from:
  - /about/
  - /about.html
---

{% include research-intro.html %}
{% include research-experience.html %}

{% assign timeline = site.data.research_timeline[0] %}
{% include research-timeline.html %}

{% include research-publications.html %}

{% for timeline in site.data.research_timeline offset:1 %}
{% include research-timeline.html %}
{% endfor %}
