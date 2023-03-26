---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="lee.joosang@gmail.com"
  link="lee.joosang@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="010-9711-7459"
  link="010-9711-7459"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="[https://www.google.com/maps](https://www.google.com/maps/place/Medical+School,+Sungkyunkwan+University+(Natural+Sciences+Campus+in+Suwon)/data=!4m14!1m7!3m6!1s0x357b42b61ce1867f:0xb38e2754eb2dbb08!2sSunkyunkwan+University+(SKKU)+-+Natural+Sciences+Campus+(NSC)!8m2!3d37.2931567!4d126.9746509!16s%2Fg%2F1tjdjnrq!3m5!1s0x357b4396ae5cea33:0xdfb5aabdeab16126!8m2!3d37.2921498!4d126.9732969!16s%2Fg%2F11h_2fw9mx)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
