---
title: Elementen een stijl geven
description: Verschillende leuke stijlregels
nextstep: stap4
weight: 300
---
We gaan het body-element nog wat meer _pimpen_. Probeer volgende aanpassing eens in je stylesheet:

{% highlight css %}
body {
    background-color:yellow;
    background-image:
        url('../images/controller.gif');
    font-family:sans-serif;
    padding:20px;
    color:#6620FF;
}
{% endhighlight %}

Je zal zien dat je pagina er weer wat anders uitziet. Een overzicht van wat er veranderd is:

<table class="deftable">
    <tr>
        <th>stijlregel</th><th>resultaat</th>
    </tr>
    <tr>
        <td markdown="span">`background-color:yellow;`</td><td markdown="span">Verandert de achtergrondkleur. Je kan heel veel zogenaamde 'keywords' gebruiken voor de kleur, zoals in dit voorbeeld `yellow`. Een volledig overzicht vind je [hier]({{ site.github.url }}/kleuren.html).</td>
    </tr>
    <tr>
        <td markdown="span">`background-image:
            url('../images/controller.gif');`</td><td markdown="span">Bepaalt een achtergrondbeeld. Standaard herhaalt dat beeld zich over de hele pagina. Met `background-repeat` kan je dat verder verfijnen.</td>
    </tr>
    <tr>
        <td markdown="span">)`font-family:sans-serif;`</td><td markdown="span">Met `font-family` kan je een lettertype kiezen. `sans-serif` is het standaard schreefloze lettertype, meestal Arial of Helvetica. `serif` is het standaard schreeflettertype. Meestal Times of Times New Roman. Je kan ook andere lettertypes gebruiken. Maar die moeten dan wel geïnstalleerd zijn op de computer van je bezoeker, of als webfont mee in je site zitten.</td>
    </tr>
    <tr>
        <td markdown="span">`padding:20px;`</td><td markdown="span">Met `padding` kan je een extra ruimte toevoegen binnen in het element. In dit geval wordt er boven, links en rechts 20 pixels ruimte vrijgehouden.</td>
    </tr>
    <tr>
        <td markdown="span">`color:#6620FF;`</td><td markdown="span">Met `color` bepaal je de kleur van tekst in een element. De waarde `#6620FF` is een manier om een kleur te noteren. Daarover in de volgende stap meer.</td>
    </tr>
</table>

Je kan ook andere elementen van je pagina een stijl geven. Probeer bijvoorbeeld eens:

{% highlight css %}
p {
    background-color:chocolate;
    font-size:20px;
    color:pink;
}
{% endhighlight %}

![Screenshot met bruine p elementen]({{ site.github.url }}/images/browser_ptagscolor.png)

Je ziet dat alle `<p>` elementen nu een bruine achtergrondkleur (chocolate) en roze tekst hebben, en dat de tekstgrootte ook veranderd is naar 20 pixels.
