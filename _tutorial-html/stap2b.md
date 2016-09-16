---
title:  Hallo wereld, achter de schermen
description: Je eerste pagina ontleed
nextstep: stap3
weight: 300
---

Ziezo, je aller-allereerste webpagina is een feit! Laten we even kijken wat deze HTML-code betekent:
<table class="deftable">
    <tr>
        <th>Lijn code</th><th>Verklaring</th>
    </tr>
    <tr>
        <td><code>{{ "<!doctype html>" | xml_escape }}</code></td><td>Dit document is van het type html.</td>
    </tr>
    <tr>
        <td><code>{{ "<html>" | xml_escape }}</code></td><td>Hier begint de HTML-code zelf.</td>
    </tr>
    <tr>
        <td><code>{{ "<head>" | xml_escape }}</code></td><td>Hier begint het hoofd ('head') van het document. Dit is niet zichtbaar voor de bezoeker.</td>
    </tr>
    <tr>
        <td><code>{{ "<title>Mijn allereerste webpagina</title>" | xml_escape }}</code></td><td>De titel van je pagina, zoals die verschijnt in de titelbalk of de tab van je browser. Ook wanneer je de pagina opslaat bij je favorieten, wordt deze titel gebruikt.</td>
    </tr>
    <tr>
        <td><code>{{ "</head>" | xml_escape }}</code></td><td>Hier houdt het onzichtbare hoofd van de pagina op. Deze tag sluit de eerdere <code>{{ "<head>" | xml_escape }}</code> weer af.</td>
    </tr>
    <tr>
        <td><code>{{ "<body>" | xml_escape }}</code></td><td>Hier begint het zichtbare deel van de webpagina, het 'lijf' of in het Engels, de 'body'.</td>
    </tr>
    <tr>
        <td><code>{{ "<p>Hallo wereld!</p>" | xml_escape }}</code></td><td>Een alinea met een beetje tekst. De 'p' komt van het Engelse 'paragraph', dat betekent alinea. Ook de volgende regel is een alinea.</td>
    </tr>
    <tr>
        <td><code>{{ "</body>" | xml_escape }}</code></td><td>Hier houdt het zichtbare gedeelte van de webpagina op. Deze tag sluit de eerdere <code>{{ "<body>" | xml_escape }}</code> weer af.</td>
    </tr>
    <tr>
        <td><code>{{ "</html>" | xml_escape }}</code></td><td>Hier houdt het html-gedeelte op. Deze tag sluit de eerdere <code>{{ "<html>" | xml_escape }}</code> weer af. Normaal komt er na deze tag niets meer.</td>
    </tr>
</table>

Zo, misschien begrijp je nu al wat meer over hoe een webpagina in elkaar zit. Probeer gerust wat te experimenteren door meer regels als <code>{{ "<p>Hallo wereld!</p>" | xml_escape }}</code> toe te voegen en de tekst te veranderen.

{% include attention.html notice="Als je aanpassingen doet, zullen die niet meteen zichtbaar zijn. Daarvoor moet je de pagina verversen. Je kan dit ook doen door de toetscombinatie CTRL-R (of Command-R op Mac) te gebruiken." %}

Je hebt zeker ook een boel nieuwe vragen. En misschien wil je ook wel wat meer kunnen dan gewoon zwarte tekst op een witte pagina? Op naar de volgende stap!
