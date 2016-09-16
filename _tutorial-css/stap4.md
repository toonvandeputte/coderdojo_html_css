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

 Je kan RGB-kleuren in css op twee manieren noteren:

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

Deze getallen zijn hexadecimaal genoteerd. Dat wil zeggen dat er zestien aparte cijfers gebruikt worden. In tegenstelling tot de tien die je gewend bent. In het decimale stelsel heb je de cijfers 0,1,2,3,4,5,6,7,8,9. In het hexadecimale heb je 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F. Voor de extra zes cijfers worden dus letters gebruikt. Laten we zo even tot 16 tellen:

<table class="deftable">
    <tr>
        <th>decimaal</th>
        <th>hexadecimaal</th>
    </tr>
    <tr>
        <td>0</td><td>0</td>
    </tr>
    <tr>
        <td>1</td><td>1</td>
    </tr>
    <tr>
        <td>2</td><td>2</td>
    </tr>
    <tr>
        <td>3</td><td>3</td>
    </tr>
    <tr>
        <td>4</td><td>4</td>
    </tr>
    <tr>
        <td>5</td><td>5</td>
    </tr>
    <tr>
        <td>6</td><td>6</td>
    </tr>
    <tr>
        <td>7</td><td>7</td>
    </tr>
    <tr>
        <td>8</td><td>8</td>
    </tr>
    <tr>
        <td>9</td><td>9</td>
    </tr>
    <tr>
        <td>10</td><td>A</td>
    </tr>
    <tr>
        <td>11</td><td>B</td>
    </tr>
    <tr>
        <td>12</td><td>C</td>
    </tr>
    <tr>
        <td>13</td><td>D</td>
    </tr>
    <tr>
        <td>14</td><td>E</td>
    </tr>
    <tr>
        <td>15</td><td>F</td>
    </tr>
    <tr>
        <td>16</td><td>10</td>
    </tr>
</table>

Het grootste getal dat je hexadecimaal met twee cijfers kan noteren is 'FF' ofwel 255. Daarom dat hexadecimaal gebruikt wordt voor compacte webkleuren.

{% include attention.html notice="Je hoeft niet van buiten te leren hoe je hexadecimaal kan tellen. Er bestaan op internet [websites](http://www.psyclops.com/tools/rgb/) die de omzetting makkelijk maken. De rekenmachine van je computer kan je ook helpen." %}

## Experimenteer zelf met RGB en HEX-kleuren
{% include kleurenmenger.html %}
