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
  - Education, Service, Skills and Languages are written by hand below.
  - Publications and Teaching are filled in automatically from the files in the
    _publications and _teaching folders, so a new paper or course only has to be
    added there.
  - The "Download CV" button serves files/Ilias_Papanikolaou_CV.pdf. To update the
    PDF, replace that file with a new one of the same name.
-->

<p class="cv-download">
  <a class="button-link" href="{{ base_path }}/files/Ilias_Papanikolaou_CV.pdf" download><i class="fas fa-download" aria-hidden="true"></i>Download CV (PDF)</a>
</p>

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

<h2 class="section-label">Service</h2>
<ul class="plain-list">
  <li><strong>Reviewer:</strong> International Conference on Learning Representations (ICLR) 2027</li>
</ul>

<h2 class="section-label">Skills</h2>
<ul class="plain-list">
  <li><strong>Programming:</strong> C/C++, Python (PyTorch), Java</li>
  <li><strong>LLM experience</strong> (CS461 coursework): implemented a neural probabilistic language model (Bengio et al.); fine-tuned BERT and a GPT-style decoder-only model for question answering and text generation, including LoRA fine-tuning</li>
</ul>

<h2 class="section-label">Languages</h2>
<ul class="plain-list">
  <li><strong>Greek:</strong> native proficiency</li>
  <li><strong>English:</strong> full professional proficiency</li>
  <li><strong>German:</strong> elementary proficiency</li>
</ul>
