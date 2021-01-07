---
layout: default
title: Thuy Vo
permalink: /
---

<div class="about">
  <div class="info">
    <h1>{{ site.author.name }}</h1>
    <p>

  My research mainly concentrates on studying the structure of random graphs.
    </p>
  </div>
  <div class="captioned-img">
    <img src="images/avatar.jpg" alt="My avatar" />
  </div>
</div>

## <i class="fas fa-university"></i> Research

{% for item in site.data.research %}
  {% assign looplenght = forloop.length %}
{% endfor %}

{% for item in site.data.research limit: 5 %}
  - <strong>{{ item.author }}</strong>. "{{ item.article }}". *{{ item.editor }}*. {{ item.more }}. {% if item.pdf %}<a href="files/pdf/{{ item.pdf }}" target="_blank">pdf</a>.{% endif %} <br />
{% endfor %}
{% if looplenght > 5 %}
  - [_See more_...](/research)
{% endif %}


## <i class="fas fa-chalkboard-teacher"></i> Teaching


{% for item in site.data.teaching %}
  {% assign looplenght = forloop.length %}
{% endfor %}

{% for item in site.data.teaching limit: 5 %}
  - <strong>{{ item.course }}</strong>. _{{ item.place }}_. {{ item.time }}. {{ item.more }}. {% if item.pdf %}<a href="files/pdf/{{ item.pdf }}" target="_blank">pdf</a>.{% endif %} <br />
{% endfor %}
{% if looplenght > 5 %}
  - [_See more_...](/research)
{% endif %}


## <i class="fas fa-mail-bulk"></i> Contact

- **Website**: [vophuongthuy.github.io](https://vophuongthuy.github.io)

- **Office**: Office 4B 090,  Bulding Copernic, LAMA - University Gustave Eiffel.
- **Address**: 5 boulevard Descartes, 77420 Champs-sur-Marne, France.

- **Email**: [{{site.author.email}}](mailto:{{site.author.email}})
