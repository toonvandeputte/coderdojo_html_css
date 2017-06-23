---
title:  Links
description: Meer dan één pagina aan elkaar linken
nextstep: stap8b-paden
weight: 900
---
Je hebt nu één webpagina gemaakt, met wat tekst op. Maar dat is nog geen website. Een website heb je pas als je meerdere pagina's aan elkaar verbindt. Dat kan je doen met links.

Maak om te beginnen een extra pagina in het mapje van je site. Noem deze pagina bijvoorbeeld `coderdojo.html`. Dan ziet je site-map er ongeveer zo uit:
<ul class="folderlist">
    <li class="folder">Mijn site
        <ul>
            <li class="folder">images</li>
            <li class="file">index.html</li>
            <li class="file">coderdojo.html</li>
        </ul>
    </li>
</ul>

Nu kan je in index.html de code aanpassen, zodat 'ie er zo uitziet:


{% highlight html %}<!doctype html>
<html>
    <head>
    <title>Mijn allereerste webpagina</title>
    </head>
    <body>
        <h1>Welkom!</h1>
        <p>Dit is mijn website, en ze gaat over wat ik leuk vind!</p>
        <h2>Mijn hobby's</h2>
        <p>Coderdojo natuurlijk, Yay!</p>
        <h3>Een opsomming</h3>
        <ul>
            <li><a href="coderdojo.html">Coderdojo</a></li>
            <li>Scouts</li>
            <li>Voetbal</li>
            <li>Lezen</li>
        </ul>
    </body>
</html>{% endhighlight %}

Je hebt nu dus een link naar coderdojo.html toegevoegd met volgende code:

{% include codecompare.html id="link" code="<a href=\"coderdojo.html\">Coderdojo</a>" %}

Op die manier kan je links naar elke pagina op het web leggen. Bijvoorbeeld ook naar Google:

{% include codecompare.html code="<a href=\"http://www.google.com\">Google</a>" %}

Om de juiste link te leggen naar een andere pagina op het internet, heb je de url ervan nodig. Die vind je in de adresbalk van je browser:

![screenshot van adresbalk]({{ site.githhub.url }}/images/screenshot_url.png)
