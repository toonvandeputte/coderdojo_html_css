---
title: CSS animatie
description: Beweging in je site
#nextstep: stap6
weight: 600
---

Met CSS kan je leuke effecten maken, met vrij weinig code. Het soort effecten waar je vroeger vaak Javascript voor nodig had, en die je nu dus gewoon met CSS kan doen.

Bijvoorbeeld een effect als dit:

<div class="flip-container">
   <div class="flipper">
      <div class="front">
      Voor
      </div>
      <div class="back">
      Achter
      </div>
   </div>
</div>

## HTML code

{% highlight html %}
<div class="flip-container">
   <div class="flipper">
      <div class="front">
      Voor
      </div>
      <div class="back">
      Achter
      </div>
   </div>
</div>
{% endhighlight %}

## CSS code

{% highlight css %}
/* de 'container', die het perspectief bepaalt */
.flip-container {
	perspective: 1000px;
}
	/* als je met de muis over de container komt, draait het kaartje om */
	.flip-container:hover .flipper, .flip-container.hover .flipper {
        /* rotatie van 180 graden om de Y-as (de verticale as) */
		transform: rotateY(180deg);
	}

.flip-container, .front, .back {
    /* De afmetingen van het kaartje */
	width: 200px;
	height: 200px;
}

/* Draaisnelheid */
.flipper {
    /* De overgang duurt 0.6 seconden */
	transition: 0.6s;
    /* Met 'transform-style' wordt aangegeven of de elementen in de 3D ruimte moeten geplaatst worden, of uitgevlakt */
	transform-style: preserve-3d;
}

.front, .back {
    /* Tijdens het roteren wordt de achterkant van het vlak verborgen. Standaard is dit een gespiegelde versie van de voorkant */
	backface-visibility: hidden;
    /* Door 'absolute' positionering kunnen voor- en achterkant bovenop elkaar worden geplaatst */
	position: absolute;
	top: 0;
	left: 0;
}

.front {
    /* De z-index is de 'stapelvolgorde' van een element. Hoe hoger, hoe meer 'bovenaan' het element komt te liggen. */
	z-index: 2;
	/* voor firefox 31 */
	transform: rotateY(0deg);
}

.back {
    /* De achterkant wordt omgedraaid */
	transform: rotateY(180deg);
}
{% endhighlight %}
