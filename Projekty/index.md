---
title: "Projekty"
layout: default
---
# {{ page.title }}

{% assign pole = "1. semester|2. semester|3. semester|4. semester|5. semester|6. semester" | split: "|" %}

## Rozdelenie podľa semestrov:

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