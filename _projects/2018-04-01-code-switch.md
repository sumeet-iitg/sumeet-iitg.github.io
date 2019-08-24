---
title: "Language Informed Modeling of Code-Switched Text"
collection: projects
permalink: /projects/2018-04-01-code-switch
date: 2018-04-01
year: 2018
paperurl: https://www.aclweb.org/anthology/W18-3211/
venue: 'ACL'
---

Code-switching (CS), the practice of alternating between two or more languages in
conversations, is pervasive in most multilingual communities. CS texts have a complex interplay between languages and occur in informal 
contexts that make them harder to collect and construct NLP tools for. We approach this problem through Language Modeling (LM) on a new Hindi-English mixed corpus 
containing 59,189 unique sentences collected from blogging websites. We implement and discuss different Language Models derived from a
multi-layered LSTM architecture. We hypothesize that encoding language information strengthens a language model by helping to learn code-switching points. We
show that our highest performing model achieves a test perplexity of 19.52 on the CS corpus that we collected and processed. On this data we demonstrate that
our performance is an improvement over AWD-LSTM LM (a recent state of the art on monolingual English).
