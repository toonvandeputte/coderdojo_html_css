---
title:  Hallo wereld
description: Je eerste pagina
nextstep: stap2b-pagina-ontleed
weight: 200
---
We gaan je allereerste webpagina maken. Die is nog heel klein. Zo doe je dat:

1. Open eerst in Atom het mapje van je site. Dat doe je via het file menu    
![Screenshot van het file menu met 'open folder' geselecteerd]({{ site.github.url }}/images/atom_open.png)
![Screenshot van het file menu met 'open folder' geselecteerd]({{ site.github.url }}/images/atom_finder.png)

1. Open in Atom een nieuw document, dat doe je ook via het file menu    
![Screenshot van het file menu met 'open folder' geselecteerd]({{ site.github.url }}/images/atom_newfile1.png)

Je hebt nu een leeg document, en daar kan je dit zetten:
{% highlight html %}<!doctype html>
<html>
    <head>
    <title>Mijn allereerste webpagina</title>
    </head>
    <body>
        <p>Hallo wereld!</p>
        <p>Hier ben ik!</p>
    </body>
</html>{% endhighlight %}
Sla het bestand op in het mapje dat je in [stap 1](stap1) gemaakt heb en geef het de naam `index.html`

<ul class="folderlist">
    <li class="folder">Mijn website
        <ul>
            <li class="file selected">index.html</li>
        </ul>
    </li>
</ul>

Als je nu dubbelklikt op dit bestandje, zal je browser openen en zie je een scherm dat lijkt op dit:
![Screenshot van een browser]({{ site.github.url }}/images/browser_helloworld.png)

Je ziet dat heel veel van de HTML-code die in je webpagina staat, niet te zien is. Daar zorgt je browser voor. Die leest het HTML-document en verwerkt het tot iets dat er veel beter leesbaar uitziet.

In de volgende stap gaan we een eerste blik werpen op wat deze code precies betekent.
