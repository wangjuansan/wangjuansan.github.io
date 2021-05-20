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
      <div class="authors">
        {{ pub.authors }}<br/>
      </div>
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
      <div class="authors">
        {{ pub.authors }}<br/>
      </div>
      {{ pub.pubin }}
    </li>
  {% endif %}
{% endfor %}
</ul>

<!--<script>document.write(Date());</script>-->
<script>
    var x = document.getElementsByClassName("authors");
    for (var i = 0; i < x.length; i++) {
        document.body.innerHTML = document.body.innerHTML.replace('Zhijie Wang', "Zhijie Wang".bold());
    }
</script>
