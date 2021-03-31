---
layout: base
css:
  - "/css/reading.css"
  - "/css/activity.css"
  - "/css/post-list.css"
---

{% include header.html type="page" %}

<!-- intro -->
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
    ref="/about#education"
    ref-title="check more"
    limit=5 %}
  {% include sections/sec-back.html %}
</section>

<!-- publications -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-publications.html
    heading="Recent publications"
    source=site.data.publications
    ref="/about#publications"
    ref-title="check more"
    limit=5 %}
  {% include sections/sec-back.html %}
</section>

<!-- research -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-timeline.html
    heading="Recent Research Experiences"
    source=site.data.research
    ref="/about#research"
    ref-title="check more"
    limit=5 %}
  {% include sections/sec-back.html %}
</section>

<!-- blog -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-blog.html %}
  {% include sections/sec-back.html %}
</section>

<!-- contact -->
<section class="alt-color">
  {% include sections/sec-front-md.html %}
  {% include sections/sec-contact.html %}
  {% include sections/sec-back.html %}
</section>
