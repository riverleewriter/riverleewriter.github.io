---
layout: base.njk
title: About
description: Brooke Lee is a Canadian, QWOC writer with a Master of Arts in Education and Gender & Women's Studies from McGill University.
---

<article class="prose about">

# About

<img class="portrait" src="/img/portrait.jpg" width="720" height="540" alt="Portrait of Brooke Lee">

Brooke Lee is a Canadian, QWOC writer with a Master of Arts in Education and Gender & Women’s Studies from McGill University. Through a historical lens, her writing centers on queer, feminist, and intersectional identity, as well as the literary arts scene of Montreal. Her work has been featured in Association of English Language Publishers of Quebec’s <em>Read Quebec</em> blog, <em>Montreal Review of Books</em>, <em>The Miramichi Reader</em>, and <em>The British Columbia Review</em>.

Brooke also writes fiction, songs, and poetry under the pen name River Lee. She is a former fiction mentee of the Quebec Writers’ Federation Mentorship Program, a Canada Council for the Arts grant recipient for her work-in-progress, debut novel (a blended work of prose and songs), and she hosts an online creative writing workshop called <a href="https://www.eventbrite.com/cc/sapphic-writes-literary-collective-4300663" rel="noopener">Sapphic Writes!</a>

<figure class="funding">
  <img src="/img/canada-council.jpg" width="577" height="106" alt="Canada Council for the Arts">
  <figcaption>2023 Research and Creation (writing as River Lee)</figcaption>
</figure>

<ul class="socials">
{% for s in site.socials %}
  <li><a href="{{ s.url }}" rel="noopener">{{ s.label }}</a></li>
{% endfor %}
</ul>

</article>
