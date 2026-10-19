---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="name == 'WeiMing Lin (林炜明)'" %}
{% include list.html data="members" component="portrait" filter="name == 'ZeRu Gong (宫泽儒)'" %}
{% include list.html data="members" component="portrait" filter="name == 'Jie Hui (惠洁)'" %}
{% include list.html data="members" component="portrait" filter="name == 'Chen Tian (田琛)'" %}
{% include list.html data="members" component="portrait" filter="name == 'QinRu Shen-Zhuang (沈庄沁儒)'" %}
{% include list.html data="members" component="portrait" filter="name == 'ZiQi Cheng (程子淇)'" %}
{% include list.html data="members" component="portrait" filter="name == 'YuCheng Bi (毕宇骋)'" %}
{% include list.html data="members" component="portrait" filter="name == 'YanYu Chen (陈彦羽)'" %}


{% include section.html background="images/background.jpg" dark=true %}

<div style="text-align: center;">Alumni</div>

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}
