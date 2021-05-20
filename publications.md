---
title: site.data.pubs.title
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
{% for pub in site.data.pubs.journal %}
  {% if pub.show %}
    * {{ pub.title }}<br/>{{ pub.authors }}<br/>{{ pub.pubin }}
  {% endif %}
{% endfor %}


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

