---
title:  Nesting
description: Nee, niets met vogels
nextstep: stap5-lijsten
weight: 550
---
Je kan de meeste elementen binnen in elkaar zetten. Bijvoorbeeld zoals in dit voorbeeld:

{% include codecompare.html id="filmpje" code="<p>
    Bekijk filmpjes op <a href=\"http://www.youtube.com/\">YouTube</a>.
</p>" %}

Je hebt hier een `a` element dat in een `p` element zit. En dat `p` element zit dan weer in het `body` element van de pagina. Dat noemen we 'nesten'.

![html ontleed]({{ site.github.url }}/images/explanations_html_example.png)

{% include attention.html notice="Als je een fout maakt bij het nesten, kan je pagina er vreemd uitzien in de browser. Het is overzichtelijk als je dan ook elk genest element een beetje inspringt. Een editor als Atom helpt je daar ook bij." %}

In de volgende stap gaan we lijsten maken, en daar komt nesten handig van pas.
