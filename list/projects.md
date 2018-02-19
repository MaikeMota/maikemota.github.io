---
title: Todos os Projetos
narrow: true
permalink: projetos
---

{% for project in site.projects %}
- [{{ project.title }}]({{ site.baseurl }}{{ project.url }})
{% endfor %}
