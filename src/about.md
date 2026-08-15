---
layout: base.njk
title: About
description: Brooke Lee is a Canadian, QWOC writer and musician based in Montreal.
---

<article class="prose about">

# About

<div class="bio">

<picture>
  <source type="image/avif" sizes="(max-width: 40em) 100vw, 16rem"
          srcset="/img/portrait-720.avif 720w, /img/portrait-1440.avif 1440w">
  <source type="image/webp" sizes="(max-width: 40em) 100vw, 16rem"
          srcset="/img/portrait-720.webp 720w, /img/portrait-1440.webp 1440w">
  <img class="portrait" src="/img/portrait-720.jpg" width="720" height="540" alt="Portrait of Brooke Lee">
</picture>

<div class="bio-text">

Brooke Lee is a Canadian, QWOC writer and musician based in Montreal. She hosts an online creative writing workshop called <a href="https://www.eventbrite.com/cc/sapphic-writes-literary-collective-4300663" rel="noopener">Sapphic Writes!</a> and her work has been featured in <em>Read Quebec</em>, <em>Montreal Review of Books</em>, <em>The Miramichi Reader</em>, and <em>The British Columbia Review</em>. In 2026, she founded <a href="https://subgenrespress.ca" rel="noopener">Subgenres</a>, a literary press for short fiction.

Brooke also writes fiction and songs under the pen name River Lee. She is a former fiction mentee of the Quebec Writers’ Federation Mentorship Program, a fiction reader for the <em>Ex-Puritan</em>, and a Canada Council for the Arts grant recipient for her work-in-progress, debut novel (a blended work of prose and songs). She’s also the event producer and host of <a href="https://www.instagram.com/sundrop.mtl" rel="noopener">SUNDROP</a>: a community platform for musicians in Montreal.

</div>
</div>

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
