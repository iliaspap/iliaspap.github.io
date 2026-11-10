---
title: 'A Simple Proof of the Exact $$(H_{k-1}+1)$$ Competitive Ratio for Explainable $$\ell_1$$ Clustering'
collection: publications
category: conferences
permalink: /publication/Simple-Proof-Explainable-l1-Clustering
excerpt: >-
  We present a simple proof that the RandomCuts algorithm for explainable clustering in the $$\ell_1$$ norm has
  competitive ratio $$H_{k-1}+1$$, where $$H_{k-1}$$ is the $$(k-1)$$th harmonic number. This bound is due to Gupta,
  Pittu, Svensson, and Yuan, who established it together with a matching lower bound for the algorithm. Gupta, Pittu,
  Svensson, and Yuan, and independently Makarychev and Shan, gave relatively simple proofs that RandomCuts is
  $$O(\log k)$$-competitive, matching the $$\Omega(\log k)$$ lower bound up to a constant factor. To establish the exact
  competitive ratio, however, Gupta, Pittu, Svensson, and Yuan used a considerably longer and more technical argument.
  In this work, building on the Set Elimination Game framework of Makarychev and Shan, we recover the exact competitive
  ratio using a short and modular analysis. An initial version of our proof established the competitive ratio
  $$\ln(k-1)+2 \approx H_{k-1}+1.423$$. During the development of this work, we used ChatGPT Pro to explore possible
  refinements. ChatGPT 5.6 Pro proposed applying Harris's inequality to strengthen a key probabilistic lemma, leading
  to the exact competitive ratio $$H_{k-1}+1$$.
date: 2027-01-15   # used for ordering only; the year shown on the site comes from "venue"
authors: "[Konstantin Makarychev](https://konstantin.makarychev.net/), Yury Makarychev, **Ilias Papanikolaou**, [Liren Shan](https://lirenshan.github.io/)"
venue: 'SOSA 2027'
to_appear: true   # shows "To appear in ..."; delete this line once the paper is published
# Optional extras - uncomment and fill in any that apply; each one adds a link under the paper.
# highlight: 'Spotlight Presentation'
# arxiv: 'https://arxiv.org/abs/XXXX.XXXXX'
# scholarurl: 'https://scholar.google.com/citations?view_op=view_citation&...'
# paperurl: 'https://iliaspap.github.io/files/your-paper.pdf'
# slidesurl: 'https://iliaspap.github.io/files/your-slides.pdf'
# posterurl: 'https://iliaspap.github.io/files/your-poster.pdf'
# codeurl: 'https://github.com/...'
---
