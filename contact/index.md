---
title: Contato
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contato

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="renomica.brasil@gmail.com"
  link="renomica.brasil@gmail.com"
%}
{%
  include button.html
  type="Endereço"
  tooltip="Nossa localização no Google Maps"
  link="https://maps.app.goo.gl/19NQiSat97TUhWQv9"
%}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
