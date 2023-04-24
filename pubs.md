---
title: Publications
layout: page
permalink: /pubs/
---

## Conference Papers
<ul>
{% for pub in site.data.pubs.conference %}
  {% if pub.show %}
    <li>
      {{ pub.title }}<br/>
      <div class="authors">
        {{ pub.authors }}<br/>
      </div>
      {{ pub.pubin }}
      {% if pub.pdf %} | <a href="{{ pub.pdf }}"><i class="far fa-file-pdf"></i></a>{% endif %}
      {% if pub.code %} <a href="{{ pub.code }}"><i class="fa fa-github"></i></a>{% endif %}
    </li>
  {% endif %}
{% endfor %}
</ul>

## Journal Papers
<ul>
{% for pub in site.data.pubs.journal %}
  {% if pub.show %}
    <li>
      {{ pub.title }}<br/>
      <div class="authors">
        {{ pub.authors }}<br/>
      </div>
      {{ pub.pubin }}
      {% if pub.pdf %} | <a href="{{ pub.pdf }}"><i class="far fa-file-pdf"></i></a>{% endif %}
      {% if pub.code %} <a href="{{ pub.code }}"><i class="fa fa-github"></i></a>{% endif %}
    </li>
  {% endif %}
{% endfor %}
</ul>

## Preprints
<ul>
{% for pub in site.data.pubs.preprint %}
  {% if pub.show %}
    <li>
      {{ pub.title }}<br/>
      <div class="authors">
        {{ pub.authors }}
      </div>
      {{ pub.pubin }}
      {% if pub.pdf %} | <a href="{{ pub.pdf }}"><i class="far fa-file-pdf"></i></a>{% endif %}
      {% if pub.code %} <a href="{{ pub.code }}"><i class="fa fa-github"></i></a>{% endif %}
    </li>
  {% endif %}
{% endfor %}
</ul>

<script>
    document.body.innerHTML = document.body.innerHTML.replace(/Zhijie Wang/g, "<u>Zhijie Wang</u>");
</script>
