---
layout: page
title: Colazione
permalink: /colazione/
---

# Colazione al Caffè Monet

Iniziate la vostra giornata con una deliziosa colazione al Caffè Monet.

## Menu Colazione

{% for item in site.data.colazione %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}