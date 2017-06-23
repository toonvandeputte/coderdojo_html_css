---
title:  Extraatje
description: Audio & video
weight: 1000
---
Er zijn nog heel veel andere HTML-elementen die je kan ontdekken en gebruiken. We lichten hier een tipje van de sluier op en tonen je er een paar van.

## video & audio

Hiermee kan je filmpjes op je webpagina zetten, zonder dat je die eerst op YouTube of zo moet uploaden. Je gebruikt dan wel best video's in het MP4 H.264 formaat. Dat zijn de meeste filmpjes met de 'mp4' extensie.

{% include codecompare.html id="mp4" code="<video
    width=\"480\"
    height=\"320\"
    controls=\"controls\">
    <source
        src=\"http://www.automaton.be/coderdojo/html_css/multimedia/parkour.mp4\"
        type=\"video/mp4\">
</video>" %}

Min of meer dezelfde code kan je gebruiken om een mp3 op je site te zetten.

{% include codecompare.html id="audio" code="<audio
    controls=\"controls\">
    <source
        src=\"http://www.automaton.be/coderdojo/html_css/multimedia/moby.mp3\"
        type=\"audio/mp3\">
</audio>" %}

## YouTube

Wil je een YouTube-filmpje op je site zetten, dan kan dat ook, met een iframe. Een iframe zorgt ervoor dat je een stukje van een andere website een plekje geeft op jouw pagina, zonder dat je hoeft door te klikken of zo. Handig, maar je filmpje zal dus wel van je pagina verdwijnen als het bij YouTube verdwijnt.

{% include codecompare.html id="video" code="<iframe
    width=\"480\"
    height=\"320\"
    src=\"https://www.youtube.com/embed/oHg5SJYRHA0\"
    frameborder=\"0\"
    allowfullscreen>
</iframe>" %}

Deze iframe-code kan je bij de meeste filmpjes op YouTube vinden:

![Never gonna give you up]({{ site.github.url }}/images/rickroll.png)

Ook bij andere sites vind je vaak 'embed' code. Je kan bijvoorbeeld ook een Scratch-project embedden op je webpagina:

![Scratch embedcode]({{ site.github.url }}/images/embed_scratch.png)

{% include codecompare.html id="scratch" code="<iframe
  allowtransparency=\"true\"
  width=\"485\"
  height=\"402\"
  src=\"//scratch.mit.edu/projects/embed/68387138/?autostart=false\"
  frameborder=\"0\"
  allowfullscreen>
</iframe>" %}
