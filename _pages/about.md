---
permalink: /
title: "Colin Graber"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Hello! I am a final year PhD Candidate at the University of Illinois at Urbana-Champaign. My research focuses on computer vision, trajectory and other types of forecasting, and interaction modeling. 

# Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include paper-single.html %}
{% endfor %}
