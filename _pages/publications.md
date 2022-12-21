---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


* **Om Maheshwari**, Ravins Katiyar, Amitava Dasgupta, Anjan Chakravorty, Deleep Nair, Nihar Mohapatra. **An Indigenous Low-Cost Robust BiCMOS Process Flow for NavIC Applications**, presented at **IEEE ICEE 2022**, Received **Best Paper Award**.   

* **Om Maheshwari**, Jiang Cao, Youseung Lee, Mathieu Luisier, Tarun Agarwal. **Radio Frequency Performance of High Mobility 2D Au2S-based Transistors**, accepted for oral presentation at **IEEE EDTM 2023**.
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
