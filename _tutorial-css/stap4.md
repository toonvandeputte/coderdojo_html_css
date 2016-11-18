---
title: Kleur
description: Kleuren mengen zoals je het (niet) kent
nextstep: stap5
weight: 400
---
Op school heb je geleerd dat geel en blauw samen groen worden, en dat rood en blauw paars is. Als je kleuren kiest voor CSS, moet je dat even vergeten. Want het scherm van een computer mengt kleuren met licht, en niet met verf. En dat werkt anders.

{% include attention.html notice="Als je wil experimenteren met CSS/HTML kleuren, kan je dat doen op de [kleuren](../kleuren.html) pagina" %}

<table class="deftable">
    <tr>
        <th>Verf</th><th>Licht</th>
    </tr>
    <tr>
        <td>Hoe meer kleuren bij elkaar, hoe donkerder</td>
        <td>Hoe meer kleuren bij elkaar, hoe lichter</td>
    </tr>
    <tr>
        <td>Je begint met wit (papier) en elke extra kleur maakt het minder wit.</td>
        <td>Je begint met zwart (scherm) en elke extra kleur maakt het meer wit.</td>
    </tr>
    <tr>
        <td>
            <img src="{{ site.github.url }}/images/colormodels-02.png" width="100%" alt="CMYK kleurmodel" />
        </td>
        <td>
            <img src="{{ site.github.url }}/images/colormodels-01.png" width="100%" alt="RGB kleurmodel" />
        </td>
    </tr>
</table>

Kleuren in css bestaan uit Rood, Groen en Blauw. Door die drie te mengen, kan je alle kleuren maken. Dat is even wennen als je enkel mengen met verf gewend bent. Je krijgt misschien niet altijd de kleur die je denkt te krijgen. Door veel met kleur te werken, leer je dat op den duur beter kennen.

Je kan RGB-kleuren in css op verschillende manieren noteren, dit zijn de voormaanste:

{% highlight css %}
body {    
    color:#6620FF;
}

body {    
    color:rgb(102,32,255);
}
{% endhighlight %}

Deze twee `color` stijlregels bepalen dezelfde kleur.

## rgb(102,32,255)

Deze manier is de meest 'leesbare'. Na het stukje 'rgb' heb je tussen haakjes de drie waarden voor de kleuren rood, groen en blauw. 255 is het grootst mogelijke getal. De kleur `rgb(255,255,255)` is wit, `rgb(0,0,0)` is zwart.

## #6620FF

Deze manier van noteren is moeilijker te lezen, maar is korter. Als je op het internet web-kleuren ziet en wil kopiëren, zal je deze notering vaak terugvinden.

Na het hekje (#) heb je daar drie getallen van twee cijfers. Het eerste (66) is de waarde van rood, het tweede (20) is groen en het derde (FF) is blauw.

Dat laatste (FF) lijkt toch helemaal niet op een getal? Dat komt omdat het *hexadecimaal* genoteerd is. Het meeste bekende getalstelsel is het decimale, waar je tien aparte cijfers hebt (0,1,2,3,4,5,6,7,8,9). In het hexadecimale stelsel heb je zestien cijfers (0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F). De letters A tot en met F worden hier dus gebruikt on een getalwaarde weer te geven, namelijk 10 tot en met 15. In het hexadecimale stelsel kan je langere getallen met minder cijfers schrijven:

![hexadecimaal telvoorbeeld]({{ site.github.url }}/images/explanations_counting_hex.png)

De '20' in het voorbeld van de webkleur is dus in feite '32', maar dan hexadecimaal genoteerd. 'FF' is de hoogst mogelijke waarde die je met twee hexadecimale cijfers kan noteren, en staat voor '255'.

{% include attention.html notice="Je hoeft niet van buiten te leren hoe je hexadecimaal kan tellen. Er bestaan op internet [websites](http://www.psyclops.com/tools/rgb/) die de omzetting makkelijk maken. De rekenmachine van je computer kan je ook helpen." %}

## Experimenteer zelf met RGB en HEX-kleuren
{% include kleurenmenger.html %}
