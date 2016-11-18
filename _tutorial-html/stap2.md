---
title:  Hallo wereld
description: Je eerste pagina
nextstep: stap2b
weight: 200
---
We gaan je allereerste webpagina maken. Die is nog heel klein.

Open je editor en typ de volgende tekst:
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
