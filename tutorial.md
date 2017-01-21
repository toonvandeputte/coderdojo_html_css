---
layout: page
title: Tutorial
menu: yes
permalink: /tutorial/
---

Wil je leren hoe je je eigen website maakt? Dat kan! En het zal je verbazen hoe snel dat gaat!

Deze tutorial is opgesplitst in verschillende delen:

## Algemeen

<ul>
{% for element in site.tutorial-intro %}
    <li><a href="{{ site.github.url }}{{element.url}}">{{element.title}}</a></li>
{% endfor %}
</ul>

## HTML

<ul>
{% for element in site.tutorial-html %}
    <li><a href="{{ site.github.url }}{{element.url}}">{{element.title}}</a></li>
{% endfor %}
</ul>


## CSS

<ul>
{% for element in site.tutorial-css %}
    <li><a href="{{ site.github.url }}{{element.url}}">{{element.title}}</a></li>
{% endfor %}
</ul>
