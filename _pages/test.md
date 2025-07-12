---
title: Test Page
layout: page
permalink: /test/
---

<h2>Publications Found:</h2>
<ul>
{% for pub in site.publications %}
  <li>{{ pub.title }}</li>
{% endfor %}
</ul>
