---
title: Todos os Projetos
narrow: true
permalink: projetos
show_profile: true
---

{% for project in site.projects %}
- [{{ project.title }}]({{ site.baseurl }}{{ project.url }})
{% endfor %}
