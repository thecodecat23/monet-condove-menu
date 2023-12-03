---
layout: page
title: Pranzo
permalink: /pranzo/
---

# Pranzo al Caffè Monet

Godetevi una pausa pranzo rilassante al Caffè Monet, dove offriamo una selezione di piatti leggeri e gustosi, perfetti per una pausa nel mezzo della giornata.

## Menu Pranzo

{% for item in site.data.pranzo %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}