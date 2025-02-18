---
Audrey SAUSSAYE : Bienvenue dans mon Portfolio
---

## Mon Parcours

{% for parcours in site.pages %}
  {% if parcours.path contains '_parcours' %}
    - [{{ parcours.title }}]({{ parcours.url }})
  {% endif %}
{% endfor %}

## Posts

{% for parcours in site.pages %}
  {% if parcours.path contains '_parcours' %}
    - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
