---
title: "Projekty"
layout: moje
obrazok1: "/obrazky/ine/rozvrh.jpg"
neuvedene: "Predmety 1-3 semestra a predmety, ktoré neobsahovali dobre zverejniteľný projekt."
opis1: "V tejto časti sa nachádzajú niektoré moje projekty, ktoré som za svoje štúdium vypracoval. Ku koncu štúdia si získali svoju stabilnú štruktúru."
opis2: "V skorších semestroch som nezvykol systematicky ukladať projekty, a tiež ich bolo veľmi málo. V prvom semestri bola hlavne matematika a teoretické predmety. To pokračovalo aj v druhom a treťom."
---

{% assign pole = "1. semester|2. semester|3. semester|4. semester|5. semester|6. semester" | split: "|" %}

> ## {{pole[3]}}	
{% for predmet in site.tags.4SEMESTER %}
> > {{ predmet.date | date_to_string }} - [{{ predmet.title }}]( {{ predmet.url }} ) 
{% endfor %}

> ## {{pole[4]}}	
{% for predmet in site.tags.5SEMESTER %}
> > {{ predmet.date | date_to_string }} - [{{ predmet.title }}]( {{ predmet.url }} ) 
{% endfor %}	
				
> ## {{pole[5]}}
{% for predmet in site.tags.6SEMESTER %}
> > {{ predmet.date | date_to_string }} - [{{ predmet.title }}]( {{ predmet.url }} ) 
{% endfor %}