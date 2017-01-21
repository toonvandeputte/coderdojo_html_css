---
title:  Lijsten toevoegen
description: Alles netjes op een rij
nextstep: stap6-prentjes
weight: 600
---
Lijsten zijn makkelijk te overlopen en lezen vaak vlotter dan een doorlopende tekst.

Je hebt in HTML twee belangrijke soorten lijsten: geordende (`<ol>`) en ongeordende (`<ul>`). De geordende worden meestal met cijfertjes weergegeven, de ongeordende met bolletjes.

De aparte puntjes in een lijst, worden altijd aangegeven met `<li>` elementen, dat staat voor 'list item'.

Je kan lijsten ook in en door elkaar gebruiken, om zo meer ingewikkelde opsommingen te krijgen.

## Geordende lijst

{% include codecompare.html code="<ol>
    <li>Stap 1</li>
    <li>Stap 2</li>
    <li>Stap 3</li>
</ol>" %}

{% include codecompare.html code="<ul>
    <li>Slaapzak</li>
    <li>Tandenborstel</li>
    <li>Pyama</li>
</ul>" %}

Probeer eens een lijst toe te voegen aan de pagina die je maakt. Zoals in het voorbeeld hieronder.
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
            <li>Coderdojo</li>
            <li>Scouts</li>
            <li>Voetbal</li>
            <li>Lezen</li>
        </ul>
    </body>
</html>{% endhighlight %}
