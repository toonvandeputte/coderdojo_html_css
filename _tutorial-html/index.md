---
title:  HTML tutorial
description: Inleiding
nextstep: stap1
weight: 10
---
Om zelf een website te maken, moet je HTML kennen. Dat leer je hier stap voor stap, door een eenvoudige webpagina te maken. We bekijken niet _alle_ mogelijkheden, maar je krijgt genoeg informatie om zelf verder op zoek te kunnen gaan.

<ul>
{% for element in site.tutorial-html %}
    <li><a href="{{element.url}}">{{element.title}}</a></li>
{% endfor %}
</ul>
