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
      {{ pub.title }}<br/>
      {{ pub.authors }}<br/>
      {{ pub.pubin }}
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
      <script>
        document.body.innerHTML = document.body.innerHTML.replace('Zhijie Wang', "<u>Zhijie Wang</u>".bold());
      </script>
      {{ pub.authors }}<br/>
      {{ pub.pubin }}
    </li>
  {% endif %}
{% endfor %}
</ul>

<!--<script>-->
<!--    var x = document.getElementsByClassName("authors");-->
<!--    for (var i = 0; i < x.length; i++) {-->
<!--        document.body.innerHTML = document.body.innerHTML.replace('Zhijie Wang', "<u>Zhijie Wang</u>".bold());-->
<!--    }-->
<!--</script>-->
