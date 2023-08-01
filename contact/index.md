---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is located in room 342 of the Biology Building at the University at Albany.

{%
  include button.html
  type="email"
  text="maxwellholteturner@gmail.com"
  link="maxwellholteturner@gmail.com"
%}

{% comment %} 
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{% endcomment %}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="[https://www.google.com/maps](https://goo.gl/maps/w2qYTpn1wzTePrxc8)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Biology Building"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Our lab"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

