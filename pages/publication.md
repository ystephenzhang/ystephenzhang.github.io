---
layout: Post
permalink: /publications
feedformat: list
title: Publications
---

My (to-be) published catalog.

{% assign pdf_files = site.static_files | where: "path", "/assets/pdf/" %}
{% for file in pdf_files %}
  - [{{ file.name }}]({{ file.path }})
{% endfor %}