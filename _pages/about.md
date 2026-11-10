---
permalink: /
title: About Me
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a fourth-year PhD student in Computer Science at [Northwestern University](https://www.northwestern.edu/), where I work with [Konstantin Makarychev](https://konstantin.makarychev.net/). My research interests lie in theoretical computer science, and more specifically, in approximation algorithms and theoretical machine learning. I am excited to design algorithms that come with theoretical guarantees and provide elegant proofs of their efficiency and accuracy. I am especially interested in clustering problems and aim to design practical algorithms for big data applications and high dimensional datasets. More broadly, I want my research to address fundamental questions in the theory of algorithms and machine learning theory and to contribute interpretable models that provide accurate solutions while remaining easy for humans to understand and validate.

Before joining the Northwestern Theory Group, I obtained my undergraduate degree in Electrical and Computer Engineering from the [National Technical University of Athens (NTUA)](https://www.ntua.gr/en/), in Athens, Greece. There, I was happy to be introduced to Theoretical Computer Science by the Theory Group of NTUA and especially Professor [Dimitris Fotakis](https://www.ece.ntua.gr/en/staff/180), who also supervised my diploma thesis on Explainable Clustering. Apart from my experience in TCS research at NTUA, I had the opportunity to engage in interesting projects on machine learning, computer vision and software engineering.

I was born and raised in Patras, Greece, where I attended the 7th High School of Patras and met my friends and inspiring teachers. 

<h2 class="section-label">Recent publications</h2>

{% for post in site.publications reversed limit: 3 %}
  {% include archive-single.html compact=true %}
{% endfor %}

<p class="more-link"><a href="{{ '/publications/' | relative_url }}">Abstracts and details on the Research page <i class="fas fa-arrow-right" aria-hidden="true"></i></a></p>
