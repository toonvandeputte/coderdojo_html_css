---
title: Paden
description: De weg vinden in je site
nextstep: stap9-audiovideo
weight: 950
---

## Een pad

Je zal in deze tutorial regelmatig het woord *pad* tegenkomen. Een pad is een soort wegwijzer naar een plaats op je computer, meestal naar een bestand of een map. Je kan een pad vergelijken met hoe je een bepaalde plaats aanduidt op de wereld. Je kan dat op verschillende manieren doen. Op het internet zijn paden meestal op dezelfe manier opgebouwd. Als je een pad goed kan 'lezen' helpt je dat enorm om je website te maken.

## Soorten pad

### Relatief pad

Dit soort pad is afhankelijk van waar je vertrekt, en werkt dus alleen als die plek waar je vertrekt niet verandert.
Als je het vergelijkt met de echte wereld, zou een 'relatief pad' naar Brussel bijvoorbeeld zijn dat die stad 50km ten Zuid-Westen van Lier ligt. Die informatie helpt je alleen als je weet dat je in Lier vertrekt. Als je enkel weet dat je 50km naar het Zuid-Westen moet gaan, maar niet waar je zou moeten vertrekken, vind je Brussel niet terug.
In een website is een relatief pad handig als je ervoor wil zorgen dat verwijzingen binnen een bepaalde map blijven werken, maar dat je die map wel kan verplaatsen.

#### Voorbeelden

<table class="deftable">
    <tr>
        <th>images/glitch.gif</th><th markdown="1">![images/glitch.gif]({{ site.github.url }}/images/path_rel1.png)</th>
    </tr>
    <tr>
        <th>../images/glitch.gif</th><th markdown="1">![images/glitch.gif]({{ site.github.url }}/images/path_rel3.png)</th>
    </tr>
    <tr>
        <th>../index.html</th><th markdown="1">![../index.html]({{ site.github.url }}/images/path_rel2.png)</th>
    </tr>
</table>

### Absoluut pad

Voorbeelden:

<table class="deftable">
    <tr>
        <th>/images/glitch.gif</th><th markdown="1">![/images/glitch.gif]({{ site.github.url }}/images/path_abs.png)</th>
    </tr>
    <tr>
        <th>http://www.google.com/</th><th markdown="1">![http://www.google.com/]({{ site.github.url }}/images/path_url.png)
        </th>
    </tr>
</table>

Dit soort pad wijst altijd dezelfde plek aan, waar je het ook gebruikt.
Als je het vergelijkt met de echte wereld, zou een 'absoluut pad' naar Brussel bijvoorbeeld zijn dat die stad op 50°51′ Noorderbreedte en 4°21′ Oosterlengte ligt. Waar je je ook op aarde bevindt, als je die informatie hebt, kan je Brussel terugvinden.
In een website is een absoluut pad handig om altijd naar dezelfde locatie te verwijzen, ook als je de pagina waar je het pad gebruikt, verplaatst.

{% include attention.html notice="Een website-adres als `http://www.google.com` is ook een soort absoluut pad, dat één bepaalde locatie aanduidt op het hele internet. Het eerste deel, 'http://', hoort er wel niet echt bij. Dat geeft aan wat voor locatie dit is, want het internet is veel meer dan alleen websites. Websites gebruiken het 'http' protocol, dus beginnen met `http://` of `https://`. In je browser hoef je dat er meestal ook niet meer bij te typen. Maar er is bijvoorbeeld ook `mailto:` waarmee bedoeld wordt dat het een e-mail verwijzing is. Probeer maar eens `mailto:toon@automaton.be` in je browserbalk te typen (maar niet Chrome)" %}
