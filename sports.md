---
layout: page
title: Sports
permalink: /sports/
---

Sports pictures

{% for file in site.static_files %}
    <img src="{{file.path}}" alt="{file.name}">
{% endfor %}
