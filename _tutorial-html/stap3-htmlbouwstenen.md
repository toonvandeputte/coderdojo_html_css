---
title:  Tags en elementen
description: De bouwstenen van HTML
nextstep: stap4-structuur
weight: 400
---
Een webpagina is dus een eenvoudig tekstdocument, met veel speciale code die een bezoeker nooit te zien krijgt. Die code is niet zichtbaar voor bezoekers, maar dient alleen om je browser te helpen om de inhoud te tonen.

De naam van die speciale code is 'HTML', wat staat voor Hypertext Markup Language. Je kan de HTML code van elke webpagina bekijken. Daarvoor rechtsklik je op een pagina en kies je 'bron bekijken' of 'view source'.

![Dropdownmenu met 'view source' uitgelicht]({{ site.github.url }}/images/dropdown_viewsource.png)

Daarna krijg je dan een venster als dit te zien:

![De broncode van een webpagina]({{ site.github.url }}/images/browser_viewsource.png)

Elke webpagina bestaat uit heel veel verschillende HTML-elementen. Bijvoorbeeld <code>{{ "<p>Hallo wereld!</p>" | xml_escape }}</code>, dat is een <code>{{ "<p>" | xml_escape }}</code> element.

![html ontleed]({{ site.github.url }}/images/explanations_html_example.png)

Zo kan je van elke pagina die je op het internet tegenkomt de broncode bekijken. Meestal zal die wel iets ingewikkelder zijn dan dit voorbeeld ;-)

Elementen bestaan uit één of meer tags. Het <code>{{ "<p>" | xml_escape }}</code> element, bijvoorbeeld, heeft een start- en een eindtag. De eindtag van een element is net hetzelfde als de begintag, maar begint met <code>{{ "</" | xml_escape }}</code> in plaats van <code>{{ "<" | xml_escape }}</code>.

![html ontleed]({{ site.github.url }}/images/explanations_html_example_elements.png)

{% include attention.html notice="De meeste HTML-code die je zelf gaat schrijven, zal je tussen `<body>` en `</body>` zetten, daar staan de dingen die zichtbaar zijn voor een bezoeker." %}

Er zijn ook elementen die maar uit één tag bestaan, zoals <code>{{ "<img />" | xml_escape }}</code>. Om die af te sluiten heb je geen extra tag nodig, maar beëindig je het element met <code>{{ "/>" | xml_escape }}</code> in plaats van <code>{{ ">" | xml_escape }}</code>. Zoals in dit voorbeeld:

{% include codecompare.html code="<img src=\"/assets/gifs/cat-pixel-12PXNbcHW8C9Bm.gif\" alt=\"nyancat\" width=\"300\" />" %}

{% include attention.html notice="Vaak worden de begrippen 'element' en 'tag' door elkaar gebruikt. Meestal kan dat geen kwaad, maar het is dus eigenlijk niet hetzelfde. Een tag is de manier waarop je een element aangeeft in een webpagina." %}

In de volgende stappen gaan we de meest gebruikte HTML elementen bekijken.
