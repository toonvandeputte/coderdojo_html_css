---
title:  Soorten afbeeldingen
description: png, gif, jpg, en...?
nextstep: stap8
weight: 800
---

Er zijn heel veel soorten afbeeldingen. Je kan ze normaal herkennen aan de extensie. Dat is het stukje bestandsnaam dat na de punt komt. Bijvoorbeeld in _afbeelding.jpg_ is 'jpg' de extensie.

De verschillende soorten afbeelding hebben vooral te maken met compressie. Dat is een manier om alle pixels van een beeld zo klein mogelijk op te slaan. Elk soort afbeeldingen doet dat op een andere manier. Elk soort afbeeldingen heeft dan ook eigen voor- en nadelen. De details hoef je niet te kennen, maar het is wel handig dat je weet welk soort afbeelding wanneer het beste geschikt is.

We zetten de verschillende soorten afbeelding even op een rijtje.

<table class="deftable">
<tr>
    <th>soort</th>
    <th>voorbeeld</th>
</tr>
<tr>
    <td>jpg</td>
    <td markdown="span" style="background-color:rgb(250,50,50);">![Coderdojo logo]({{ site.github.url }}/images/compressie.jpg)
    </td>
</tr>
<tr>
    <td>gif</td>
    <td markdown="span" style="background-color:rgb(250,50,50);">![Coderdojo logo]({{ site.github.url }}/images/compressie.gif)
    </td>
</tr>
<tr>
    <td>png</td>
    <td markdown="span" style="background-color:rgb(250,50,50);">![Coderdojo logo]({{ site.github.url }}/images/compressie.png)
    </td>
</tr>
</table>

## jpeg
Jpeg wordt vooral gebruikt voor foto's en andere afbeeldingen die geen scherpe kleurvlakken hebben. De compressie van jpeg zorgt er namelijk voor dat scherpe lijnen en volle kleuren 'vuil' en vager worden. Bij foto's zie je dat niet.

![De 'images' folder]({{ site.github.url }}/images/compressie.jpg)

Je maakt jpegs met een fotobewerkingsprogramma als Gimp. De meeste digitale fototoestellen slaan hun foto's ook meteen op als jpeg. Om die op je website te gebruiken, maak je ze best eerst wel kleiner.

## gif
Dit is het oudste soort afbeeldingen voor het web. Een gif kan maximum 256 kleuren bevatten. Dat merk je vooral als je kleurrijke foto's als gif wil opslaan.
Een gif kan transparant zijn, maar elke pixel is ofwel helemaal onzichtbaar ofwel helemaal zichtbaar. Daardoor zie je soms kartelranden.

![De 'images' folder]({{ site.github.url }}/images/compressie.gif)

Het grootste voordeel van gifs is dat je gif-animaties kan maken. Die zijn meestal wel heel erg groot (in megabytes), dus je houdt ze best klein en kort.

Je maakt _animated gifs_ online of met een programma als Gimp. Maar je kan er ook heel veel kant en klaar vinden op Giphy.

## png
Dit is de 'modernste' veelgebruikte soort afbeeldingen voor het web. png's kunnen een transparante achtergrond hebben, zelfs gedeeltelijk doorschijnend. Het belangrijkste nadeel aan png is dat je er geen animatie in kan stoppen.

![De 'images' folder]({{ site.github.url }}/images/compressie.png)

Je maakt png's met een fotobewerkingsprogramma als Gimp. Online kan je bijvoorbeeld Pixlr gebruiken.

## svg
SVG hoort niet helemaal thuis in dit lijstje, want het is een _vectorieel_ soort afbeelding. Dat betekent dat een svg afbeelding niet bestaat uit pixels, maar uit lijnen en punten. Dat betekent dat je een svg-afbeelding zo groot kan maken als je wil, zonder dat je pixels begint te zien. Voor eenvoudige vormen, zoals logo's, is svg meestal ook erg klein.

SVG is eigenlijk ook code, die lijkt op HTML . Je kan svg ook meteen in je website als code schrijven. De details daarvan gaan we hier niet uitleggen, maar hier is een voorbeeld:

{% include codecompare.html code='<svg
  xmlns="http://www.w3.org/2000/svg"
  version="1.1"
  width="100%"
  height="160"
  xmlns:xlink="http://www.w3.org/1999/xlink">
  <polygon
    class="shape"
    points="150,75 112.5,140 37.5,140 0,75 37.5,10 112.5,10"
    fill="#FF0000">
  </polygon>
  <circle
    class="shape"
    transform="translate(150 0)" r="65" cx="75" cy="75"
    fill="#0000FF">
  </circle>
</svg>' %}

SVG-afbeeldingen maak je in een programma als Inkscape of Illustrator.
