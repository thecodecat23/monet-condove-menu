---
layout: page
title: Birre
permalink: /birre/
---

# Birre al Caffè Monet

Scoprite la nostra selezione curata di birre locali e internazionali.

## Menu delle Birre

{% for item in site.data.birre %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}