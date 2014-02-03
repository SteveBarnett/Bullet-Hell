---
layout: post-no-feature
title:
category: articles
tags: []
linky:
---

{% if page.linky %}
<a href="{{page.linky}}">![{{ page.title }}](/images/.jpg)</a>
{% else %}
![{{ page.title }}](/images/.jpg)
{% endif %}

*

[{{ page.title }}]({{page.linky}})