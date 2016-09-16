---
title: Classes en ID's
description: Net dat éne element een stijl geven
nextstep: stap6
weight: 500
---
Met de HTML en CSS die je nu kent, kan je al wat kleur en afbeeldingen toevoegen aan je pagina.
In de vorige stap hebben we bijvoorbeeld alle `<p>` elementen een bruine achtergrondkleur gegeven.
Maar wat als je maar één van die twee p's een bruine achtergrond wil geven? Dat kan! En daarvoor gebruik je classes en/of id's.

## Een class toevoegen en gebruiken

Voeg een attribuut `class` toe aan één van de `<p>` elementen in je webpagina, verander bijvoorbeeld `<p>Coderdojo natuurlijk, Yay!</p>` in `<p class="speciaal">Coderdojo natuurlijk, Yay!</p>`.

Daarna kan je bijvoorbeeld deze code aan je stylesheet toevoegen:

{% highlight css %}
.speciaal {    
    background-color:red;
}
{% endhighlight %}

En dan krijg je ongeveer dit:

![screenshot van webpagina]({{ site.github.url }}/images/screenshot_class.png)

Een class is dus een ander manier om een bepaald element op een pagina uit te kiezen. Je kan verschillende elementen op dezelfde pagina dezelfde class geven. Dat is ook de bedoeling, 'class' betekent 'klasse'. Het is dus een manier om elementen dezelfde 'soort' te geven.

Laten we één van de `li` elementen uit de opsomming dezelfde class geven:

{% highlight html %}
<li class="speciaal">Coderdojo</li>
{% endhighlight %}

Zodat de hele lijst er zo uitziet:

{% highlight html %}
<ul>
    <li class="speciaal">Coderdojo</li>
    <li>Scouts</li>
    <li>Voetbal</li>
    <li>Lezen</li>
</ul>
{% endhighlight %}

Als je je pagina dan in je browser opent, zie je dit:

![screenshot van webpagina]({{ site.github.url }}/images/screenshot_class2.png)

Je kan een class ook specifiek maken voor een bepaald element. Dat doe je zo:

{% highlight css %}
li.speciaal {    
    background-color:red;
}
{% endhighlight %}

Nu zullen enkel `li` elementen met de class `speciaal` een rode achtergrond krijgen:

![screenshot van specifieke selector]({{ site.github.url }}/images/screenshot_selector.png)

## Een ID toevoegen en gebruiken

Voeg een attribuut `id` toe aan het `h1` element op je webpagina, zodat je `<h1 id="paginatitel">Welkom!</h1>` krijgt.

Daarna kan je deze code aan je stylesheet toevoegen:

{% highlight css %}
#paginatitel {    
    background-color:blue;
    color:white;
}
{% endhighlight %}

De titel van je pagina heeft nu een blauwe achtergrond en witte tekst:

![screenshot van blauwe paginatitel]({{ site.github.url }}/images/screenshot_pagetitle.png)

Een ID doet dus eigenlijk hetzelfde dan een class. Maar er is een belangrijk verschil: Een ID mag maar één keer op een pagina voorkomen. ID's dienen namelijk om één specifiek element aan te duiden. Ze worden ook vaak gebruikt door Javascript om een bepaald element op een pagina terug te vinden. Zoals bijvoorbeeld in dit lijstje:

{% highlight html %}
<ul>
    <li class="kind" id="kind1">Thijs</li>
    <li class="kind" id="kind2">Klaas</li>
</ul>
{% endhighlight %}

Je ziet dat de twee `li` elementen dezelfde class `kind` hebben, maar een verschillende ID. Als je toch hetzelfde ID twee of meer keer gebruikt op een pagina, zullen de meeste browsers daar niet moeilijk over doen, maar het is een slechte gewoonte. Best niet doen, dus.  
