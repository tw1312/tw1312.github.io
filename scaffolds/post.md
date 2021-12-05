---
title: {{ title }}
date: {{ date }}
tags:
- yiwu
- sheng
year: 1999
updated: {{ date }}
comments: true
price: 4
gramm: 100
---

![ExamplePicture](setup.jpeg)

Width Height
{% asset_img "setup.jpeg" 900 650 "Rareness6 Setup"  %}
<img src="setup.jpeg" width="400" height="400" alt="Bla" title="bla">

Preview text here. The title is {{ title }}

Some js tests
{% set items = [1,2,3,4,5,6] %}
{% set dash = joiner("-") %}
{% for item in items | batch(2) %}
    {{ dash() }} {% for items in item %}
       {{ items }}
    {% endfor %}
{% endfor %}


{{ price / gramm * 3.14 }}

<!-- more -->

Preview ends here.

# Rating

# Tasting Diagram

# Statistics & Reference
- Brewing time
- Purchased for {{ price }}
- Vendor & Link

