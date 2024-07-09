---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?user=MjUm33wAAAAJ&hl=zh-CN">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
1. Jointly Texture Enhanced and Stereo Captured Network for Stereo Image Super-Resolution <br>  **Kangjun Jin**, Xuejin Wang, Fengshao* <br> Pattern Recognition Letters, 2023 <a href="https://www.sciencedirect.com/science/article/abs/pii/S0167865523000442">[PDF]</a>
