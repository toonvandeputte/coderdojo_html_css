---
layout: page
#title: HTML elementen
menu: no
permalink: /htmlels/
---

De structuur van een HTML document wordt bepaald door HTML elementen. De meeste elementen bestaan uit een start- en een eindtag.

Door het gebruik van HTML elementen kan je browser van een eenvoudig tekstdocument een website met links, afbeeldingen, enzovoort, maken.

Hieronder vind je voor de meest belangrijke HTML elementen meer informatie. Over waarvoor ze dienen en hoe je ze kan gebruiken.

<ul>
{% for element in site.htmlels %}
    <li><a href="{{element.url}}">{{element.title}}</a></li>
{% endfor %}
</ul>
