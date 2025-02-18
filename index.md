---
Audrey SAUSSAYE : Bienvenue dans mon Portfolio
---

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Mon Parcours

{% for parcours in site.pages %}
  {% if parcours.path contains '_mon parcours' %}
    - [{{ parcours.title }}]({{ parcours.url }})
  {% endif %}
{% endfor %}
