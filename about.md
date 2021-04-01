---
layout: base
title: About me
css:
  - "/css/activity.css"
  - "/css/project.css"
js:
  - "/js/jquery-2.1.3.min.js"
---

{% include header.html type="page" %}

<!-- introduction -->
<section class="alt-color">
{% include sections/sec-front-md.html %}

<div class="txt-center" markdown="1">
I am **Thuy**, a Mathematician and a Math teacher. My research focuses on the field of random graphs, in particular, the exploration process in random networks. I am also interested in the estimation problem for some models applied in Biology and Sociology. One of my desires is to make more connections between Vietnam and France, in order to open up new oppotunities for Vietnamese students to get access the advanced study and research. 
</div>

{% include sections/sec-back.html %}
</section>

<!-- education -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-timeline.html
    heading="Education"
    source=site.data.education
    ref="education" %}
  {% include sections/sec-back.html %}
</section>

<!-- publications -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-publications.html
    heading="Publications"
    source=site.data.publications
    ref="publications"%}
  {% include sections/sec-back.html %}
</section>

<!-- research -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-timeline.html
    heading="Research Experiences"
    source=site.data.research
    ref="research" %}
  {% include sections/sec-back.html %}
</section>

<!-- teaching -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-teaching.html
    heading="Teaching"
    source=site.data.teaching
    ref="teaching" %}
  {% include sections/sec-back.html %}
</section>

<!-- contact -->
<section class="alt-color">
  {% include sections/sec-front-md.html %}
  {% include sections/sec-contact.html %}
  {% include sections/sec-back.html %}
</section>
