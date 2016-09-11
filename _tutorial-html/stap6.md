---
title:  Afbeeldingen
description: Jeuj! Prentjes!
nextstep: stap7
weight: 700
---
We hebben tot nu toe alleen nog maar tekst toegevoegd. Maar de échte fun begint als je afbeeldingen kan toevoegen.

Voor afbeeldingen gebruik je het `<img>` element. Hier moet je voor het eerst ook attributen gaan gebruiken. Dat is extra informatie die je aan een tag toevoegt. Bij een afbeelding is dat bijvoorbeeld de verwijzing naar waar de afbeelding staat.

{% include codecompare.html code='<img
    src="/assets/gifs/cat-pixel-12PXNbcHW8C9Bm.gif"
    alt="nyancat"
    width="300" />' %}

<table class="deftable">
    <tr>
        <th>attribuut</th><th>Betekenis</th>
    </tr>
    <tr>
        <td>src</td>
        <td>De afkorting van 'source', of 'bron' in het Nederlands. Dit is de plek waar je afbeelding staat. </td>
    </tr>
    <tr>
        <td>alt</td>
        <td>Een korte tekstbeschrijving van de afbeelding. Wordt gebruikt door blinde bezoekers, en door Google</td>
    </tr>
    <tr>
        <td>width / height</td>
        <td>De breedte en hoogte, in pixels, waarop je de afbeelding wil tonen. Dit kan je gebruiken om een afbeelding groter of kleiner te tonen. Als je maar één van deze attributen gebruikt, wordt de andere automatisch in verhouding berekend. Handig!</td>
    </tr>
</table>

## Juist verwijzen naar afbeeldingen

Om afbeeldingen toe te voegen aan je site, zet je die best in een apart mapje. Maak in het mapje waar je je site hebt staan een nieuwe map en noem die <em>images</em>. Daarin kan je dan afbeeldingen zetten die je kan gebruiken.

![De 'images' folder](/images/folder_images.png)

Als je in index.html als src-attribuut `images/glitch-flashing-MpEb9fz3M1lZe.gif`, dan betekent dit dat de browser het beeld `glitch-flashing-MpEb9fz3M1lZe.gif` gaat zoeken in de map `images`.

<table class="deftable">
    <tr>
        <th>src</th>
        <th>waar staat de afbeelding?</th>
    </tr>
    <tr>
        <td>
        "images/glitch-flashing-MpEb9fz3M1lZe.gif"
        </td>
        <td>
        <ul class="folderlist">
            <li class="folder">Mijn site
                <ul>
                    <li class="file">index.html</li>
                    <li class="folder">images
                        <ul>
                            <li class="file selected">glitch-flashing-MpEb9fz3M1lZe.gif</li>
                        </ul>
                    </li>
                </ul>
            </li>

        </ul>
        </td>
    </tr>
    <tr>
        <td>
        "glitch-flashing-MpEb9fz3M1lZe.gif"
        </td>
        <td>
        <ul class="folderlist">
            <li class="folder">Mijn site
                <ul>
                    <li class="file">index.html</li>
                    <li class="file selected">glitch-flashing-MpEb9fz3M1lZe.gif</li>
                </ul>
            </li>

        </ul>
        </td>
    </tr>
</table>

Op zoek naar leuke afbeeldingen? Het internet staat vol, maar we hebben ook al <a href="/assets/gifs.zip">de leukste prentjes van het hele internet</a> verzameld.

Kopieer een paar afbeeldingen die je leuk vindt naar je eigen _images_ map en probeer ze toe te voegen aan je site.

{% highlight html %}<!doctype html>
<html>
    <head>
    <title>Mijn allereerste webpagina</title>
    </head>
    <body>
        <h1>Welkom!</h1>
        <img
            src="images/glitch-flashing-MpEb9fz3M1lZe.gif"
            width="400"
            alt="decepticon logo" />
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

In de volgende stap gaan we kijken naar welke soorten afbeeldingen je kan gebruiken.
