---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is located in room 342 of the Biology Building at the University at Albany.

We are always interested in welcoming new members to our lab. If you would like to learn more, or hear about the opportunties in the lab, please reach out to Max directly!

{%
  include button.html
  type="email"
  text="mhturner@albany.edu"
  link="mhturner@albany.edu"
%}

{% comment %} 

{%
  include button.html
  type="phone"
  text="(518) 442-4208"
  link="+1-518-442-4208"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="[https://www.google.com/maps](https://goo.gl/maps/w2qYTpn1wzTePrxc8)"
%}

{% endcomment %}


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

