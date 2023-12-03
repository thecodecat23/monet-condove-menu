---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Benvenuti al Caffè Monet, Condove
---

## Menu
Benvenuti al Caffè Monet, Condove

- [Benvenuti al Caffè Monet, Condove](#benvenuti-al-caffè-monet-condove)
  - [Menu](#menu)
    - [Colazione](#colazione)
    - [Pranzo](#pranzo)
    - [Aperitivo](#aperitivo)
    - [Birre](#birre)

### Colazione
{% for item in site.data.colazione %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}

### Pranzo
{% for item in site.data.panetteria_e_pizzeria %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}

### Aperitivo
{% for item in site.data.aperitivo %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}

### Birre
{% for item in site.data.birre %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}