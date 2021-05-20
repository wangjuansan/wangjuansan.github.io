---
title: Publications
layout: page
permalink: /publications/
---

<script>
function boldMe(var1) {
  return var1.replace("Zhijie Wang", "DT");
}
</script>

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
    var new_name = {{ pub.authors }}
    <li>
      {{ pub.title }}<br/>
      {{ boldMe(pub.authors) }}<br/>
      {{ pub.pubin }}
    </li>
  {% endif %}
{% endfor %}
</ul>


<!--* Image-level to Pixel-wise Labeling: From Theory to Practice<br/>-->
<!--Tiezhu Sun, Wei Zhang, <u>Zhijie Wang</u>, Lin Ma, Zequn Jie<br/>-->
<!--The 27th International Joint Conference on Artificial Intelligence (IJCAI 2018)-->

<!--* Salient Object Detection by Pyramid Networks with Gating<br/>-->
<!--Mingxin Zhang, **Zhijie Wang**, Tiezhu Sun, Xiaolei Li<br/>-->
<!--The 2019 IEEE International Conference on Robotics and Biomimetics (ROBIO 2019)-->

<!--## Journal Papers-->

<!--* Salient Object Detection with Adversarial Training<br/>-->
<!--**Zhijie Wang**, Wei Zhang, Xuewen Rong, Yibin Li<br/>-->
<!--IET Image Processing-->

<!--* EFNet: Enhancement-Fusion Network for Semantic Segmentation<br/>-->
<!--<u>Zhijie Wang</u>, Ran Song, Peng Duan, Xiaolei Li<br/>-->
<!--Pattern Recognition-->

