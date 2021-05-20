---
title: Publications
layout: page
permalink: /publications/
---

## Conference Papers
<ul>
{% for pub in site.data.pubs.conference %}
  {% if pub.show %}
    <li>
      {{ pub.title }}<br/>{{ pub.authors }}<br/>{{ pub.pubin }}
    </li>
  {% endif %}
{% endfor %}
</ul>

## Journal Papers
<ul>
{% for pub in site.data.pubs.journal %}
  {% if pub.show %}
    <li>
      {{ pub.title }}<br/>{{ pub.authors }}<br/>{{ pub.pubin }}
    </li>
  {% endif %}
{% endfor %}
</ul>
