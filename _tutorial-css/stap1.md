---
title: Starten met CSS
description: Het juiste bestand op de juiste plaats
nextstep: stap2
weight: 100
---
Vooraleer je CSS begint te schrijven, gaan we er eerst voor zorgen dat je de juiste mapjes en bestanden hebt.
Maak in het mapje van je site een nieuwe map 'css' aan:

<ul class="folderlist">
    <li class="folder">mijn site
        <ul>
            <li class="folder">images</li>
            <li class="folder selected">css</li>
            <li class="file">index.html</li>
            <li class="file">coderdojo.html</li>
        </ul>
    </li>
</ul>

In Atom maak je nu een nieuw bestand `stylesheet.css` aan in je nieuwe `css` map:

![Bestand aanmaken '/css/stylesheet.css']({{ site.github.url }}/images/atom_filename.png)

In dit bestand gaan we CSS stijlen schrijven.

![Screenshot van Atom]({{ site.github.url }}/images/atom.png)

Maar we moeten er nog voor zorgen dat onze webpagina deze stijlen ook gaat gebruiken. Daarvoor moeten we een regel tekst toevoegen aan het `<head>` element van je webpagina.

{% highlight html %}<link rel="stylesheet" href="css/stylesheet.css" />{% endhighlight %}

De `<head>` van je webpagina ziet er dan ongeveer zo uit:

{% highlight html %}
<head>
    <title>Mijn allereerste webpagina</title>
    <link rel="stylesheet" href="css/stylesheet.css" />
</head>{% endhighlight %}

Ziezo, nu is je stylesheet.css bestand klaar om te bewerken en weet je webpagina waar 'ie het moet gaan zoeken. Kunnen we eindelijk iets leuks gaan doen!
