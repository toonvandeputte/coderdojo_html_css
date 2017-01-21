---
title:  Titels toevoegen
description: Een beetje structuur in je pagina
nextstep: stap4b-vogels
weight: 500
---
We hebben al een eenvoudige webpagina gemaakt. Daar gaan we nu wat titels aan toevoegen.

Titels zorgen ervoor dat mensen langere teksten makkelijker kunnen lezen. Bovendien zijn titels belangrijk voor Google: een woord dat in de titel staat, vindt Google belangrijker dan een woord in gewone tekst.

Titel-tags beginnen altijd met `h`, en er zijn verschillende niveaus. De belangrijkste titel is `h1`, en de minst belangrijke is `h6`.

{% include codecompare.html code="<h1>Hoofding</h1>
<h2>Hoofding</h2>
<h3>Hoofding</h3>
<h4>Hoofding</h4>
<h5>Hoofding</h5>
<h6>Hoofding</h6>" %}

Probeer eens wat titels toe te voegen aan de pagina die je maakt, tussen de `<body>` en `</body>` tags, in het body-element dus. Zoals in het voorbeeld hieronder.
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
    </body>
</html>{% endhighlight %}
