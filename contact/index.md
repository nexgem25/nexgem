---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact
Our lab is part of the group of [Prof. Joosang Lee] of the [Department of Medicine](https://www.skkumed.ac.kr/), and [Department of Artificial Intelligence](https://ai.skku.edu/ai/index.do)

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
  text="Google Maps"
  link="https://goo.gl/maps/FFT3neNXtRJo8mgp8"
  style="button"
 %}
 {:.center}

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
