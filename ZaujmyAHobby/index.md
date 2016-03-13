---
title: "Záujmy a koníčky"
layout: default
---

# {{ page.title }}

Záujmy:
{% for zaujem in site.tags.ZAUJEM %}
> > {{ zaujem.date | date_to_string }} - [{{ zaujem.title }}]( {{ zaujem.url }} ) 
{% endfor %}

Koníčky:
{% for hobby in site.tags.HOBBY %}
> > {{ hobby.date | date_to_string }} - [{{ hobby.title }}]( {{ hobby.url }} ) 
{% endfor %}
