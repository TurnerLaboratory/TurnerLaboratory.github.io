---
title: Lab members
nav:
  order: 3
  tooltip: Lab members
---

# {% include icon.html icon="fa-solid fa-users" %}Lab members


{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: mgr" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!.*\b(pi|mgr|phd|alumni)\b).*$" %}

{% include section.html %}

## Alumni

{% include list.html  data="members" filters="role: alumni" %}


