---
title: Lab members
nav:
  order: 3
  tooltip: Lab members
---

# {% include icon.html icon="fa-solid fa-users" %}Lab members

We are always interested in welcoming new members to our lab. If you would like to learn more, or hear about the opportunties in the lab, please reach out to Max directly (maxwellholteturner [at] gmail.com)

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include grid.html style="square" content=content %}
