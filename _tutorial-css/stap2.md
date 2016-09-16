---
title: Hoe werkt CSS?
description: De basis
nextstep: stap3
weight: 200
---
Het eerste wat we gaan doen, is wat kleur toevoegen aan die witte pagina.
Open je stylesheet.css bestand en voeg volgende regels toe:

{% highlight css %}
body {
    background-color:yellow;
}
{% endhighlight %}

Als je dit opslaat, en je opent vervolgens je webpagina in een browser, dan zal je zien dat 'ie een gele achtergrondkleur heeft. Jeuj!

![Screenshot van gele webpagina]({{ site.github.url }}/images/browser_yellow.png)

Als we dan de kleur van de tekst ook willen aanpassen, doen we:

{% highlight css %}
body {
    background-color:yellow;
    color:blue;
}
{% endhighlight %}

Wat je nu gemaakt hebt is één 'ruleset', of 'regelset' in het Nederlands. Met deze CSS-code zorg je ervoor dat het hele `<body>` element een gele achtergrond heeft ('yellow' in het Engels). Het stuk `body {}` noemen we de *selector*. De regels die daarin staan, zoals `color:blue;` zijn de stijlregels. Zo'n stijlregel bestaat uit een eigenschap (`color` in het voorbeeld) en een waarde (`blue` in het voorbeeld). Daartussen staat een dubbelepunt.

{% include attention.html notice="Bij CSS is het belangrijk dat je alles juist schrijft, belangrijker dan bij HTML. Je moet er op letten dat je geen `}` vergeet, bijvoorbeeld. En ook de puntkomma op het einde van elke stijlregel is belangrijk. Als je die vergeet, dan zal je CSS niet werken." %}

In de volgende stap gaan we kijken welke soorten stijlregels je zoal kan gebruiken.
