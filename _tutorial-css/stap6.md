---
title: Complexe selectors
description: Goed kunnen kiezen is belangrijk
nextstep: stap7
weight: 600
---

Je kan heel specifiek kiezen welk element een bepaalde stijlregel meekrijgt. Een overzicht van handige selectors, met voorbeelden:

<table class="deftable">
    <tr>
        <th>Selector</th><th>Betekenis</th>
    </tr>
    <tr>
        <td markdown="span">`p,ul`</td><td markdown="span">Geldt voor `p` elementen én `ul` elementen.</td>
    </tr>
    <tr>
        <td markdown="span">`ul li`</td><td markdown="span">Geldt alleen voor `li` elementen die in een `ul` element zitten. </td>
    </tr>
    <tr>
        <td markdown="span">`body > a`</td><td markdown="span">Geldt alleen voor `a` elementen die op het eerste niveau in een `body` element zitten. Deze selector geldt dus niet voor `a` elementen die een niveau dieper, bijvoorbeeld in een `p` element, zitten.</td>
    </tr>
    <tr>
        <td markdown="span">`p + ul`</td><td markdown="span">Geldt alleen voor `ul` elementen die vlak na een `p` element komen.</td>
    </tr>
    <tr>
        <td markdown="span">`p.speciaal.belangrijk`</td><td markdown="span">Geldt alleen voor `p` elementen de class `speciaal` én de class `belangrijk` hebben.</td>
    </tr>
    <tr>
        <td markdown="span">`img[src$=".png"]`</td><td markdown="span">Geldt alleen voor `img` elementen waarvan het src attribuut eindigt met `.png`. Alle png-afbeeldingen, dus.</td>
    </tr>
    <tr>
        <td markdown="span">`a[href^="https://"]`</td><td markdown="span">Geldt alleen voor `a` elementen waarvan het href attribuut begint met `https://`. Alle beveiligde links, dus.</td>
    </tr>
    <tr>
        <td markdown="span">`a[href*="scratch.edu"]`</td><td markdown="span">Geldt alleen voor `a` elementen waarvan het href attribuut ergens `scratch.edu` bevat. Dus links naar iets op de Scratch website.</td>
    </tr>
</table>
