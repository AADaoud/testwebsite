---
layout: single
permalink: /amino-acids/
---
{% for amino-acid in site.amino-acids %}
  <h2>{{ amino-acid.name }} - {{ amino-acid.classification }}</h2>
  >{{ amino-acid.content | markdownify }}
  ![image]({{amino-acid.image}})
{% endfor %}