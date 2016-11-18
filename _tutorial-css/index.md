---
title:  CSS tutorial
description: Inleiding
nextstep: stap1
weight: 10
---
Met CSS ('Cascading Style Sheets') kan je zelf helemaal bepalen hoe een pagina eruit ziet. CSS is ook een soort computertaal, speciaal bedoeld om aan te passen hoe een webpagina er uitziet. Om dat goed te kunnen doen, moet je wel eerst een basiskennis van HTML hebben. Die kan je opdoen via de [HTML tutorial]({{ site.github.url }}/tutorial-html). We bekijken niet _alle_ mogelijkheden, maar je krijgt genoeg informatie om zelf verder op zoek te kunnen gaan.

Eens je een beetje HTML onder de knie hebt, kan je met CSS aan de slag om de boel een beetje leuker te maken. Net als bij CSS is het zo dat je heel eenvoudig kan beginnen, en dat je zelf verder op ontdekking kan gaan en nieuwe dingen leren. In deze tutorial zetten we je op weg, maar _alle_ mogelijkheden van CSS uitleggen, dat kunnen we hier niet.

<ul>
{% for element in site.tutorial-css %}
    <li><a href="{{ site.github.url }}{{element.url}}">{{element.title}}</a></li>
{% endfor %}
</ul>
