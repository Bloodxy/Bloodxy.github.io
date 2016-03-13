---
layout: default
title: "Cestovanie - galéria"
date: 2016-03-7
tag: "HOBBY"
obrazok1: "zeneva"
obrazok2: "vitaznyObluk"
obrazok3: "versailes"
obrazok4: "stiavnica"
obrazok5: "spaniaDolina"
obrazok6: "praha"
obrazok7: "montBlanc"
obrazok8: "eifelovka"
---

# {{ page.title }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok1] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok2] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok3] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok4] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok5] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok6] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok7] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}

{% assign obrazok = site.data.cestovanieDATA[page.obrazok8] %}  
<img src="{{ site.url }}{{ obrazok.img }}">

**Rok:** {{ obrazok.rok }}
**Opis:** {{ obrazok.opis }}
