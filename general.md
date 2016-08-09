---
permalink: /general
layout: default
category: general
title: System Security Plan - General System Description
tags:
---
{% for system in site.collection.system %}
  [{{ policy.title }}]({{ site.baseurl }}/policy/{{ policy.title }})
{% endfor %}
