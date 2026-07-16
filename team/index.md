---
title: Lab members
nav:
  order: 3
  tooltip: Lab members
---
# The Lab


{% include figure.html image="images/lab_bouldering.jpeg" caption="Lab photo July 2026 - bouldering!" %}

# {% include icon.html icon="fa-solid fa-users" %}Lab members


{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: mgr" %}
{% include list.html data="members" component="portrait" filters="role: tech" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!.*\b(pi|mgr|phd|ms|tech|alum)\b).*$" %}

# {% include icon.html icon="fa-solid fa-hand-peace" %}Alumni
{% include list.html data="members" component="portrait" filters="role: alum" style="small"%}
