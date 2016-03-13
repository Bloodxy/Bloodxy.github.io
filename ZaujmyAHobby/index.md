---
title: "Záujmy a koníčky"
layout: moje
obrazok1: "/obrazky/ine/friends.jpg"
neuvedene: "filmy, psy, mačky, seriály"
opis1: "V tejto časti sa nachádzajú moje záujmy a koníčky. Každá kategória obsahuje fotky (prípadne aj videá) o konkrétnych veciach, ktorým sa venujem alebo ma zaujímajú."
opis2: "Tieto všetky som bližšie nešpecifikoval z dôvodu, že sa im aktívne nevenujem, ale sú fajn. Rád pozerám filmy, ale do kina nechodím. Psa nevlastním, aj keď som ho vždy chcel. Seriály si občas pozriem, ale zaberajú príliš veľa času. Na strednej škole som veľa cestoval."
---
> Záujmy:
{% for zaujem in site.tags.ZAUJEM %}
> > {{ zaujem.date | date_to_string }} - [{{ zaujem.title }}]( {{ zaujem.url }} ) 
{% endfor %}

> Koníčky:
{% for hobby in site.tags.HOBBY %}
> > {{ hobby.date | date_to_string }} - [{{ hobby.title }}]( {{ hobby.url }} ) 
{% endfor %}
