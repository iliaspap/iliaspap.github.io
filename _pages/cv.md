---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!--
  How to edit this page
  - Education, Skills and Languages are written by hand below.
  - Publications and Teaching are filled in automatically from the files in the
    _publications and _teaching folders, so a new paper or course only has to be
    added there.
-->

<h2 class="section-label">Education</h2>
<ul class="entry-list">
  <li class="entry">
    <div class="entry__body">
      <h3 class="entry__title">Ph.D. in Theoretical Computer Science</h3>
      <p class="entry__sub"><a href="https://www.northwestern.edu/">Northwestern University</a></p>
      <p class="entry__sub">Advised by <a href="https://konstantin.makarychev.net/">Konstantin Makarychev</a></p>
    </div>
    <div class="entry__date">2023 &ndash; present<br>(expected 2028)</div>
  </li>
  <li class="entry">
    <div class="entry__body">
      <h3 class="entry__title">Integrated Master (MEng) in Electrical and Computer Engineering</h3>
      <p class="entry__sub"><a href="https://www.ntua.gr/en/">National Technical University of Athens</a></p>
      <p class="entry__sub">Diploma thesis on explainable clustering, supervised by <a href="https://www.ece.ntua.gr/en/staff/180">Dimitris Fotakis</a></p>
    </div>
    <div class="entry__date">Oct. 2017 &ndash; Apr. 2023</div>
  </li>
</ul>

<h2 class="section-label">Publications</h2>
<ul class="entry-list">
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

<h2 class="section-label">Teaching</h2>
<ul class="entry-list">
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

<h2 class="section-label">Skills</h2>
<ul class="plain-list">
  <li><strong>Programming languages:</strong> C/C++, Python, Java</li>
  <li><strong>Machine learning:</strong> hands-on experience with large language models (LLMs), gained through the Northwestern graduate course CS461 - &ldquo;Deep Learning for Natural Language Processing&rdquo;</li>
</ul>

<h2 class="section-label">Languages</h2>
<ul class="plain-list">
  <li><strong>Greek:</strong> native proficiency</li>
  <li><strong>English:</strong> full professional proficiency</li>
  <li><strong>German:</strong> elementary proficiency</li>
</ul>
