---
layout: post-no-feature
title:
category: articles
tags: []
linky:
img:
---

{% if page.linky %}
<a href="{{page.linky}}">![{{ page.title }}](/images/{{page.img}})</a>
{% else %}
![{{ page.title }}](/images/{{page.img}})
{% endif %}

- 

{% if page.linky %}
[{{ page.title }}]({{page.linky}})
{% endif %}
