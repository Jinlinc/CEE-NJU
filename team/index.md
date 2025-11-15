---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="name == 'Chen Tian (田琛)'" %}
{% include list.html data="members" component="portrait" filter="name == 'Jie Hui (惠洁)'" %}
{% include list.html data="members" component="portrait" filter="role == 'programmer'" %}
{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% include section.html background="images/background.jpg" dark=true %}

三人行，必有吾师。
