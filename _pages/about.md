---
permalink: /
layout: research
redirect_from:
  - /about/
  - /about.html
---

{% include research-intro.html %}

<p class="bio">At KAIST, I was advised by Professors <a href="http://www.sungjuhwang.com/">Sung Ju Hwang</a> and <a href="https://juho-lee.github.io/">Juho Lee</a> in the <a href="https://www.mlai-kaist.com/">Machine Learning and Artificial Intelligence (MLAI) Lab</a>. I also collaborate closely with <a href="https://ml.comp.nus.edu.sg/kawaguchi">Kenji Kawaguchi</a>. I was a recipient of the <a href="https://machinelearning.apple.com/updates/apple-scholars-aiml-2023">2023 Apple Scholars in AI/ML PhD Fellowship</a>.</p>

{% include research-experience.html %}

{% assign timeline = site.data.research_timeline[0] %}
{% include research-timeline.html %}

{% include research-publications.html %}

{% for timeline in site.data.research_timeline offset:1 %}
{% include research-timeline.html %}
{% endfor %}
