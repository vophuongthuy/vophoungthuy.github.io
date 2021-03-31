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
My name is Dinh Anh **Thi** (call me Thi), a Vietnamese guy who
is curious about everything. I start from an amateur mathematician and a
curious learner. I like to write about applied maths, apps and tools which
are helpful for the human life. I also like to [read](#), to [travel](#) and to meet
people.
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
