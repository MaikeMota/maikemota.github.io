---
layout: defaults/page
permalink: index
narrow: true
---

{% include components/intro.md %}

[Saiba mais sobre mim.]({{ site.baseurl}}{% link _pages/about.md %})

<!-- <div class="card mb-3">
    <img class="card-img-top" src = "https://drscdn.500px.org/photo/143841823/q%3D80_m%3D1500/v2?webp=true&sig=3c0fa3b75ac4098ca23a31d681a6bc4d2dc91877294fd966dd202aa5b5eb3688"/>
    <div class="card-body bg-light">
        <div class="card-text">A picture from when John was on holiday in the Peak District.</div>
    </div>
</div> -->

### Projetos

Area destinada aos projetos


### Portfólio

Area destinada ao Portifólio


### Postagens

Area Destinada as postagens

### Postagens Recentes

{% for post in site.posts limit:5 %}
{% include components/post-card.html %}
{% endfor %}


